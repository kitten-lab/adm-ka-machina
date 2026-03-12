# Entity Ven System

**one-law ontology** of AIDM:

> **Everything is a VEN.**

All attributes and functions of a ven emerge from **properties and dynamics**.

	VEN
	  ├ properties
	  └ dynamics

And one structural property flag:

`isContainer`

Which means the world graph is simply:

	VEN → contains → VEN

That’s it.

So examples become trivial.

### A room
	ven.Room_221  
	  prop: isContainer=true  
	  contains:  
	      ven.Bed_03  
	      ven.Table_02  
	      ven.Mira_01

### Mira
	ven.Mira_01  
	  prop: isCharacter=true  
	  contains:  
	      ven.Lipstick_04  
	      ven.MemoryGraph

### A quest
	ven.Quest_VampireNight  
	  prop: isContainer=true  
	  contains:  
	      ven.Event_Intro  
	      ven.Event_Hunt  
	      ven.Event_Reveal

### A world
	ven.World_Skyline  
	  prop: isContainer=true  
	  contains:  
	      ven.District_A  
	      ven.District_B  
	      ven.District_C


Structurally **everything is the same *object of potential***.

Only the **properties change the meaning**.