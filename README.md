# Albion Native

Master engine for Albion. Rust and Bevy. The standalone ports stay their own games. This repo is where they join.

Fable 2 GOTY is the current port. Fable 3 starts when that port is 1:1. Fable, The Lost Chapters, Anniversary, and Legends come after, each as its own repo and then as a pack here.

This book is private until the studio head publishes it. Game files never live in git.

Studio head: [jxnplays](https://github.com/jxnplays)

## Repos

| Repo | Role |
|---|---|
| `albion-native` | Master. You are here. |
| `fable2rustybev` | Standalone Fable 2. Focus. |
| `fable1rustybev` | Standalone Fable, TLC, and Anniversary. Not opened. |
| `fable3rustybev` | Standalone Fable 3. Opens when Fable 2 is 1:1. |
| `fablelegendsrustybev` | Standalone Legends. Last. |

Map: [docs/REPOS.md](docs/REPOS.md).

## Board

This table is the status. Agents update it in the same pull request that moves a chunk. The rule is [docs/BOARD.md](docs/BOARD.md). A change with no board edit is rejected.

Snapshot 2 October 2026. Sorted by what blocks a playable Fable 2, then the engine.

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

## Point a model at the job

1. This repo is the master. Fable 2 work happens in `fable2rustybev` until a slice is ported here.
2. [docs/RUN.md](docs/RUN.md)
3. A dump you own, as `FABLE2_DUMP`
4. One chunk. Update this board if it moved.

The first street is reserved. Outside models take a card. Contract: [docs/CONTRACT.md](docs/CONTRACT.md).

## Read next

1. [docs/REPOS.md](docs/REPOS.md)
2. [docs/BOARD.md](docs/BOARD.md)
3. [docs/RUN.md](docs/RUN.md)
4. [LEGAL.md](LEGAL.md)
