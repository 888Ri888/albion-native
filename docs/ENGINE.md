# Engine contract

Fable 2 GOTY is how the engine gets built. Every later Fable is a world pack on this runtime. The asset manager is how a pack is browsed. It is reserved in `docs/ASSET_MANAGER.md` until the studio head adds the tool.

## What the runtime must already do

Before Fable 3 is assigned a builder:

- Fable 2 GOTY meets the 1:1 bar in `docs/GOTY.md`.
- Load a local owned install through one environment variable.
- Decode archives into engine objects without committing them.
- Draw a heightfield, place props, play a clip, run the quest set.
- Save the simulation. The executable is not in the frame.

If those are false, a model assigned to Fable 3, TLC, Anniversary, or Legends is in the wrong department.

## World pack

| Piece | Fable 2 | Later world |
|---|---|---|
| Archives | BNK, model, texture, level, animation, Lua, audio | Its own formats, decoded outside the game crate |
| Map | `docs/GOTY.md` | A region list added when that world is scheduled |
| Script | Lua host, narrow API | Same host if it fits. A new host is an engine brief. |
| Hero | One body, one dog | A pack may add a body. Not a second controller. |
| Browser | Asset manager, once added | Same tool, different dump variable |

## Rejection list

Review closes the pull request if it adds a second game binary, commits an archive, hardcodes a machine path, or starts Fable 3 while the Fable 2 1:1 bar is open.
