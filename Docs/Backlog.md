# Repaired · Feature backlog and scope plan

## Backlog (MoSCoW)

| Feature | MoSCoW | Why | Effort (S/M/L) |
|---|---|---|---|
| Main menu with Start and Quit | Must | Allows the player to begin and exit the game | S |
| Pause menu with Resume and Return to Menu | Must | Allows the player to pause and leave a session | S |
| Horizontal movement and collisions | Must | Allows exploration of the village | S |
| Village street, five small interiors, and doorway transitions | Must | Provides the locations needed for the investigation | M |
| Object inspection and interaction prompts | Must | Allows players to discover clues and understand usable objects | M |
| Small inventory with item selection and use | Must | Supports collecting parts and using them on appropriate targets | M |
| Notebook containing clues and current objectives | Must | Keeps evidence available for solving puzzles | M |
| Authored dialogue that responds to discovered evidence | Must | Connects investigation progress to character conversations | L |
| Bird diagnosis puzzle | Must | Introduces inspection and identifies the required repair parts | S |
| Linkage measurement puzzle | Must | Provides a replacement part and reveals Lina’s earlier repairs | M |
| Spring selection puzzle | Must | Makes players use Lina’s notes to select a suitable component | M |
| Parcel investigation puzzle | Must | Uses a receipt number and address clues to reveal Lina’s plans | M |
| Bird stand assembly puzzle | Must | Connects the collected objects and explains their intended purpose | M |
| Puzzle feedback and safe retries | Must | Allows mistakes without losing items or blocking progress | S |
| Story progression retained between locations | Must | Keeps items, solved puzzles, and conversations consistent during play | M |
| Mara’s final decision and bakery epilogue | Must | Completes the customer’s story and explains why the repair is deferred | M |
| Ending screen with Replay and Main Menu | Must | Clearly concludes the game and allows a fresh playthrough | S |
| Optional hints for each puzzle | Should | Helps players continue when they become stuck | M |
| Save and Continue between sessions | Should | Lets players finish the chapter across multiple sessions | M |
| Consistent AI-assisted artwork, music, sound effects, and UI | Should | Supports the atmosphere and the generative-assets milestone | L |
| Adjustable text size and audio volume | Should | Improves readability and comfort | M |
| Doorbell tutorial before the main case | Could | Introduces item use and Mara’s personality | S |
| Extra conversations and inspectable village details | Could | Adds humor and character without affecting progression | M |
| Small ambient animations | Could | Makes the village feel more alive | S |
| Jumping, combat, or 3D movement | Won’t | Outside the intended exploration and puzzle experience | L |
| Entering memory worlds | Won’t | Discoveries come from objects and village conversations | L |
| Additional customers and Homecoming festival | Won’t | Keeps the semester focused on one complete story | L |
| Large branching storyline or live AI-generated dialogue | Won’t | Adds complexity and risks contradictions in the mystery | L |
| Multiplayer, real-time deadlines, or shop decoration | Won’t | Unnecessary for the core experience | L |
| Full voice acting | Won’t | Text dialogue keeps production manageable | L |

## Scope plan

| Deadline | What must be playable | Backlog items |
|---|---|---|
| HA02 — Prototype — Lesson 7 | A short complete repair investigation: accept the request, inspect the bird, visit Ivo, solve the measurement puzzle, obtain a part, and report back. Include a clear prototype completion screen. Placeholder art and shortened dialogue are acceptable. | Movement, basic locations and transitions, inspection, inventory, basic dialogue, diagnosis, measurement, feedback, and session progression |
| HA03 — Agentic Workflow — Lesson 10 | The full chapter can be played from the main menu to Mara’s decision and the bakery epilogue, using placeholder assets where needed. | All five puzzle sequences, all required locations, evidence-dependent dialogue, notebook, menus, ending, and replay |
| HA04 — Generative Assets — Lesson 12 | AI-made visuals, music, sound effects, and UI are integrated into the playable chapter. Clues and interaction targets remain readable. | Artwork, audio, UI, and presentation polish |
| Final — 3 days before Lesson 14 | Every Must is complete and tested in a Windows build. Incorrect answers, revisiting locations, and replaying cannot block progress. | All Musts; remaining Shoulds only after the complete game works reliably |

The Lesson 7 prototype demonstrates one complete core-loop cycle; the full story ending is planned for Lesson 10. Although presentation assets are Should features for gameplay scope, their integration is scheduled for the required Lesson 12 milestone.

## Riskiest Must and Plan B

**Risk:** Evidence-dependent dialogue and progression across several locations could become inconsistent, causing repeated rewards, missing conversations, or blocked objectives.

**Plan B:** Use a fixed sequence of investigation stages, one active objective at a time, and a single relevant conversation per character at each stage. Remove optional dialogue branches and simplify puzzle interfaces to item selection or number entry while preserving the essential evidence and ending.