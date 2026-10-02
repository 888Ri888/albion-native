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

This is the status. Agents update the row they moved, in the same pull request. Rule: [docs/BOARD.md](docs/BOARD.md). A change with no board edit is rejected.

Snapshot 2 October 2026. Sorted inside each section by what blocks the next shot.

### Boot

| # | Chunk | % | Why |
|---|---|---|---|
| 1 | `FABLE2_DUMP` set and listing `default.xex` | 10 | Name exists. Working tree says the dump is not mounted. |
| 2 | Archive index from that dump | 40 | BNK reads have happened. Not a clean boot test in this book. |
| 3 | Window titled Albion Native | 60 | A native window has opened. Not tied to a dump. |

### First street

| # | Chunk | % | Why |
|---|---|---|---|
| 4 | One GLB in the Bevy scene | 0 | Converter output is not in the window. |
| 5 | One texture on that mesh | 0 | No applied texture. |
| 6 | Bloodstone heightfield under the body | 0 | Files parse. Ground is not drawn. |
| 7 | One prop from the placement table | 0 | 19,463 instances parsed. None placed. |
| 8 | Collision on that ground | 0 | Greybox move exists. Not on the heightfield. |
| 9 | Shot of mesh, texture, and ground | 0 | Sunday bar. |

### Formats

| # | Chunk | % | Why |
|---|---|---|---|
| 10 | Model decoder | 70 | 941 of 986 convert. Foliage open. |
| 11 | Foliage sub-format | 0 | Trees and grass do not convert. |
| 12 | Texture decoder | 20 | Headers decode. About 100 of 1,339 convert. |
| 13 | Level records | 35 | Bloodstone scenario and heightfield files parse. |
| 14 | Animation clips | 40 | 4,082 clips mapped. Curve mode still wrong. |
| 15 | Lua bytecode | 30 | 1,378 scripts extracted. None run. |
| 16 | Audio banks | 25 | 47,071 cues extracted. None play. |

### Hero and town

| # | Chunk | % | Why |
|---|---|---|---|
| 17 | Greybox body | 40 | Moves. Not a Fable mesh. |
| 18 | Idle, walk, run clips on that body | 0 | Samples exist. Not playing. |
| 19 | Game mesh replaces greybox | 0 | Not started. |
| 20 | Dog follow and stay | 0 | Plan only. |
| 21 | Dog point and grow | 0 | Plan only. |
| 22 | Lock-on | 0 | Not in the build. |
| 23 | One melee | 0 | Not in the build. |
| 24 | One spell | 0 | Not in the build. |
| 25 | One ranged weapon | 0 | Not in the build. |
| 26 | First quest starts and completes | 0 | Cards indexed. No script host in the running game. |
| 27 | Rest of the Fable 2 quest cards | 5 | Names listed. None evidenced. |
| 28 | One job | 0 | Blocked on a street. |
| 29 | Stall buy and sell | 0 | Not started. |
| 30 | Rent tick | 0 | Not started. |
| 31 | Two expression channels | 0 | Not started. |
| 32 | Morality moves from a cited act | 0 | Not started. |
| 33 | Health and will orbs | 5 | Spec only. |
| 34 | Minimap stub | 0 | Not in the build. |
| 35 | One audio cue | 0 | Banks extracted. No playback. |
| 36 | One save slot | 0 | Not in the build. |

### Regions

| # | Chunk | % | Why |
|---|---|---|---|
| 37 | Bloodstone street | 15 | Data only. |
| 38 | Bowerstone Market | 0 | Not drawn. |
| 39 | Old Town | 0 | Childhood start. Not drawn. |
| 40 | Bower Lake and the road | 0 | Not drawn. |
| 41 | Oakfield | 0 | Not drawn. |
| 42 | Westcliff | 0 | Not drawn. |
| 43 | Wraithmarsh | 0 | Not drawn. |
| 44 | Knothole Island | 0 | Pack. Not scheduled. |
| 45 | See the Future | 0 | Pack. Not scheduled. |

### Tools, mods, engine

| # | Chunk | % | Why |
|---|---|---|---|
| 46 | `list_region` | 0 | Named. Not a call. |
| 47 | `remake` one record | 0 | Named. Not a call. |
| 48 | `spawn_prop` and `shot` | 0 | Named. Not a call. |
| 49 | Path edit | 0 | Named. Not a call. |
| 50 | Asset manager hooked up | 0 | Tool exists outside this repo. Not added. |
| 51 | Pack loader | 0 | No second world can mount. |
| 52 | Mod drop-in that does not commit a dump | 5 | Legal rule exists. No loader. |
| 53 | Fable 2 GOTY 1:1 | 6 | Formats only. |
| 54 | Master loads Fable 2 as a pack | 0 | Blocked on 53. |
| 55 | `fable3rustybev` opened | 0 | Starts when 53 is real. |
| 56 | Fable 3 1:1 | 0 | Not started. |
| 57 | `fable1rustybev` opened | 0 | After Fable 3 is playable. |
| 58 | Anniversary presentation on TLC | 0 | Not started. |
| 59 | `fablelegendsrustybev` | 0 | Last. Legal source only. |

Sunday bar is rows 4, 5, 6, and 9. Not row 53.

## Point a model at the job

1. This repo is the master. Fable 2 work happens in `fable2rustybev` until a slice is ported here.
2. [docs/RUN.md](docs/RUN.md)
3. A dump you own, as `FABLE2_DUMP`
4. One row. Update this board if it moved.

The first street is reserved. Outside models take a card. Contract: [docs/CONTRACT.md](docs/CONTRACT.md).

## Read next

1. [docs/REPOS.md](docs/REPOS.md)
2. [docs/BOARD.md](docs/BOARD.md)
3. [docs/RUN.md](docs/RUN.md)
4. [LEGAL.md](LEGAL.md)
