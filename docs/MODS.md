# User meshes

Not built. This is the contract so a Blender file and a game mesh share one loader.

A user exports GLB. They drop it in a local `mods/` folder that is not committed. The loader that already spawns a converted Fable mesh spawns this one. No second pipeline.

| Tag | Means |
|---|---|
| `companion` | Follows the hero. The dog is the first slot. A second file does not replace quest logic. |
| `mount` | Hero attaches. Blocked until the body collides with the street. |
| `mob` | Hostile or ambient. Uses the combat chunk once that chunk exists. |
| `prop` | Sits where it is placed. |

A name override from `docs/NPCS.md` can label any of these. Voice, quests, and the original dog id are unchanged unless a card says otherwise.

Plug and play means the drop folder plus a tag. It does not mean an unrigged mesh animates. A companion needs a clip, or it stands. Sunday still comes first. This folder is empty until I-04 has a shot.
