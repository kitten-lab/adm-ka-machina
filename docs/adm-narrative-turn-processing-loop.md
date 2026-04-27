# ADM — Narrative Processing Loop

ADM operates through a turn-based narrative processing system.

Each turn represents a cycle where player input is interpreted, evaluated, and transformed into the next state of the world.

## 1. Player Input

The player performs an action within the world.

- The player is equipped with a Ven (their current active identity or role).
- The player interacts with other Vens (characters, objects, environments).
- Relevant Vens are "checked out" into the active context based on the interaction.

This defines the current narrative moment.

---

## 2. Transfer to Reasoning Layer

The player’s action is passed to the reasoning layer via their agent (Amen).

The reasoning layer includes:
- ADM (the narrative intelligence governing the world)
- System intelligences (“system girls”) responsible for data access and structure

---

## 3. Reasoning Process

Within the reasoning layer, a structured evaluation occurs:

- Relevant Vens and world state are retrieved
- Nearby relationships, history, and context are considered
- Possible narrative outcomes are generated

This process evaluates:
- coherence with existing narrative
- impact on the player’s experience
- impact on the world’s ongoing timeline (server state)

The goal is to determine outcomes that:
> maximize narrative satisfaction for both the player and the world

---

## 4. Outcome Selection

Multiple possible outcomes may be considered.

ADM and the system intelligences evaluate these options and select the most appropriate next narrative step.

---

## 5. Output to Player

The selected outcome is returned to the player through their Amen.

- The response is expressed through the active **VOX pack**
- The VOX pack defines the tone, voice, and narrative style of the experience

This becomes the next narrative moment.

---

## 6. State Update

The world updates based on the outcome:

- Vens update their state and history
- Relationships and conditions may change
- The world timeline (server instance) progresses

---

This loop repeats continuously, allowing narrative to evolve through interaction.
