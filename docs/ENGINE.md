# Engine contract

Fable 2 GOTY is how the engine gets built. Fable 3, Fable: The Lost Chapters, and Fable Legends do not get their own runtimes. They get world packs on this one, after the Fable 2 spine can be walked.

A world pack is data plus a thin registration. It is not a fork.

## What the runtime must already do

Before a second world is assigned a builder:

- Load a local owned install through one environment variable. Fable 2 uses `FABLE2_DUMP`. Later worlds get their own variable, same rule.
- Decode archives into engine objects without committing the archives.
- Draw a heightfield, place props, play a clip, run one scripted quest.
- Save the simulation. The executable is not in the frame.

If those four are false, a model assigned to Fable 3 or Legends is in the wrong department.

## World pack

| Piece | Fable 2 GOTY | Later world |
|---|---|---|
| Archives | BNK, model, texture, level, animation, Lua, audio | Its own formats, decoded in `albion_formats`, not in the game crate |
| Map | Regions in `docs/GOTY.md` | Its own region list, added to `docs/WORLDS.md` when scheduled |
| Script | Lua host, narrow API | Same host if the script model fits. A new host is an engine brief, not a quiet extra. |
| Hero | One body, one dog | A pack may add a body. It may not add a second player controller. |
| Rules | Combat, morality, jobs | Overrides are data. A hardcoded second combat system is a rejection. |

## Later worlds

| World | What "content and assets" means | When |
|---|---|---|
| Fable 3 | Owned install, its maps and scripts as a pack on this runtime. | After the Fable 2 spine is playable. |
| Fable: The Lost Chapters | Older engine. Asset and rule study first. Not a copy of the Fable 2 decoders. | Not scheduled. |
| Fable Legends | Closed beta is a restore problem. No ISO is assumed. A pack exists only if the operator has a legal source. | Not scheduled. |

## Rejection list

Review closes the pull request if it adds a second game binary, commits an archive, hardcodes a machine path, or starts TLC or Legends while Bloodstone is still unrendered.
