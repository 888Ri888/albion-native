# Agent tools

The player can hand a live model a seat in the running project. That seat can list, convert, replace, and respawn assets from an install the operator owns. That is the access. It is not an administrator login on the machine.

## Seat

| Power | Allowed | Refused |
|---|---|---|
| Read the dump | Through `FABLE2_DUMP` only | Any other disk path |
| Remake an asset | Write a derived mesh, texture, or clip into the local generated directory | Commit the dump, the derived file, or a ripped original |
| Replace in the scene | `spawn_prop`, `move_prop`, delete that placement | Edit unrelated project files mid-prompt |
| See the result | `shot` of the current view | A hidden channel outside the repository |
| Paths | `trace_path` on the loaded region | Traffic data from another game |

Remake means derive. A model becomes a GLB. A texture becomes an engine image. The original archive stays in the dump. The agent does not get root, a shell outside the tool list, or the right to publish the result.

## Tools

| Tool | Does |
|---|---|
| `list_region` | Loaded street, exits, prop counts. |
| `list_assets` | Records in the dump the manager can see. |
| `remake` | Convert one named record into the local generated directory. |
| `spawn_prop` | Place that derived record. |
| `move_prop` | Move or delete that placement. |
| `trace_path` | Read or write a road or NPC path. |
| `shot` | Return the current frame. |

One prompt, one tool, then a shot. A quest or a combat number is still a chunk in `docs/SYSTEMS.md`.

## Proof

The first proof is `remake` on one non-foliage model, `spawn_prop`, and `shot`. If the dump variable is unset, the seat stops and writes `BLOCKED`.
