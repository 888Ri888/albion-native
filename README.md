# Albion Native

Albion Native is my engine for Albion. One runtime, written in Rust and Bevy. Fable 2 GOTY is the first rewrite and the thing that makes the engine real. Fable 3 starts when that rewrite is 1:1. The other Fable games join as world packs.

This repository is the production book. It is private until the studio head publishes it. Running code stays in the private working tree until a slice is ported here. Game files never live in git.

Studio head: [jxnplays](https://github.com/jxnplays)

## Board

Snapshot 2 October 2026. A row moves only when a pull request proves it. Sorted by what blocks a playable Fable 2, then the engine.

| # | Chunk | % | Why it is this number |
|---|---|---|---|
| 1 | Owned dump hooked up | 10 | Variable is named. Working tree still says the dump is not mounted. |
| 2 | First street on screen | 0 | No mesh, texture, and ground in one shot. |
| 3 | Level draw | 15 | Bloodstone parses, about 19,000 props. Nothing is drawn. |
| 4 | Texture on a mesh | 8 | About 100 of 1,339 textures convert. None applied in a scene. |
| 5 | Model conversion | 70 | 941 of 986 models become GLB. Foliage is open. Not in the window. |
| 6 | Native window and body | 25 | Window, menu, and a greybox player. Not a Fable body. |
| 7 | Animation on that body | 20 | 4,082 clips decoded. Curve mode is wrong. Not playing. |
| 8 | First quest | 5 | Scripts extracted. None run. Cards are indexed only. |
| 9 | Combat | 0 | Not in the running game. |
| 10 | Dog | 0 | Follow is a plan, not a system. |
| 11 | Jobs, morality, HUD, audio, save | 5 | Specs and parked prototypes. Not the build. |
| 12 | Live agent tools | 5 | Seat is written. No `remake` or `shot` call exists. |
| 13 | Mod support | 5 | Dump stays local. No pack loader yet. |
| 14 | Asset manager | 0 | Required. Not in this repo. |
| 15 | Fable 2 GOTY 1:1 | 6 | Formats exist. Regions, quests, and packs do not run. |
| 16 | Engine holds a second world | 0 | Blocked on row 15. |
| 17 | Fable 3 | 0 | Starts the day row 15 is real. |
| 18 | Fable, TLC, Anniversary, Legends | 0 | Named. Not scheduled. |

Sunday bar is rows 2, 4, and 3 in one shot. Not row 15.

## Lineup

| Order | World |
|---|---|
| Now | Fable 2 GOTY, including Knothole Island and See the Future |
| When Fable 2 is 1:1 | Fable 3, then its packs |
| After Fable 3 is playable | Fable, The Lost Chapters, Anniversary as presentation on TLC |
| Last, legal source only | Fable Legends |

Detail is in [docs/LINEUP.md](docs/LINEUP.md).

## Point a model at the job

1. [docs/RUN.md](docs/RUN.md)
2. A dump you own, as `FABLE2_DUMP`
3. One chunk from [docs/SYSTEMS.md](docs/SYSTEMS.md) or one card from [docs/LORE.md](docs/LORE.md)
4. Chunk, department, builder, review

The first street is reserved. Outside models take a card. Contract: [docs/CONTRACT.md](docs/CONTRACT.md).

## What this is not

- Not a decompilation of an executable.
- Not an emulator.
- Not a strategy guide.
- Not a claim that any Fable already runs 1:1.

## Read next

1. [REVIEW.md](REVIEW.md) before this is public.
2. [docs/RUN.md](docs/RUN.md) to start a model.
3. [docs/SYSTEMS.md](docs/SYSTEMS.md) and [docs/LORE.md](docs/LORE.md) to take a chunk.
4. [docs/ASSET_MANAGER.md](docs/ASSET_MANAGER.md) for the tool still to be added.
5. [LEGAL.md](LEGAL.md) before anyone touches a dump.
