# Status

Updated 2 October 2026. This page is the public progress board. If a sentence is not backed by a merged pull request, it does not go here.

## Now

The project can read a local Fable 2 GOTY dump and describe its archives. It can convert most models to GLB. It can open a Bevy window and move a greybox body. It cannot yet show Bloodstone.

## Formats

| Format | Public claim |
|---|---|
| Model archives | Decoder and GLB writer exist. 941 of 986 models convert. Foliage is a separate sub-format and is open. |
| Textures | Headers decode. Full conversion is early, on the order of 100 of 1,339. |
| Levels | Bloodstone scenario parses, including prop instances and heightfield files. Not drawn. |
| Animation | Clip table and sample decoder exist. Curve mode still emits bad values. |
| Scripts | Lua 5.1 bytecode is extracted and documented. A quest does not run yet. |
| Audio | Banks can be listed and extracted. Playback is not in the runtime. |

## Runtime

| Piece | Public claim |
|---|---|
| Window | Opens under the Albion Native title. Vulkan is the known-good backend on the development GPU. |
| Menu | Present. |
| Player | Greybox movement and a follow camera. |
| Combat, dog, HUD, save | Designed and prototyped. Not the running game until they land on main through a pull request. |
| Town render | Not started in the public tree. |

## Not started

Quests, jobs, expressions, morality, economy, co-op, cinematics, Knothole Island, See the Future, Fable 3, Fable TLC, Fable Legends.

## How to read the bars

Archive work is the strong half. The game is the empty half. A 1:1 GOTY port is early. This page will not say otherwise.
