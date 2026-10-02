# Agent tools

The interaction to match is a short prompt that calls tools, changes the world, and shows the result. The reference is a San Andreas demo: a model builds a mesh, explores a map, and edits path nodes, three prompts at most. Those GTA tools are not this project. The loop is.

Albion Native needs the same loop on Fable 2, then on the engine.

## Tools the runtime must expose

| Tool | Does | GTA demo equivalent |
|---|---|---|
| `list_region` | Names the loaded street, exits, and prop counts. | Map explorer |
| `spawn_prop` | Places one record from the local dump by id. | Build a landmark |
| `move_prop` | Moves or deletes that placement. | Edit the scene |
| `trace_path` | Reads or writes a road or NPC path. | Traffic nodes |
| `shot` | Returns a frame of the current view. | Visual check |

The asset manager is the browser behind `spawn_prop`. Until that tool is added, the converter is the browser. No tool accepts a path. The dump variable is already set.

## Session rule

The player, or a model the player assigned, types a short brief. The runtime runs one tool, then shows the shot. It does not rewrite the engine mid-prompt. A quest, a combat number, or a new region is still a chunk in `docs/SYSTEMS.md`, not a side effect of a prompt.

## Doable

Yes, once a street renders. The first proof is `spawn_prop` of one converted model and `shot` of that frame. Map explore and path edit come after the heightfield exists. This does not require the San Andreas repositories, and it does not ship their assets.
