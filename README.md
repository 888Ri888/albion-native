<p align="center">
  <img src="docs/brand/mark.svg" alt="Albion Native. One Rust and Bevy engine for every Fable." width="880">
</p>

<p align="center">
  <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <img src="https://img.shields.io/badge/Bevy-runtime-c4a574?style=for-the-badge" alt="Bevy">
  <img src="https://img.shields.io/badge/work-ports%20%7C%20engine%20%7C%20tools-6b2d3c?style=for-the-badge" alt="Ports, engine, tools">
</p>

This page is the project. Albion Native is one Rust and Bevy engine. Each Fable is its own port, then a world on this runtime. Fable 2 GOTY is the only port with code. Studio head: [jxnplays](https://github.com/jxnplays). Official game art is not in this repo.

The build is `fable2rustybev` at `6802309`. [docs/CATCHUP.md](docs/CATCHUP.md). A row on this page moves only when that change is proven. [docs/BOARD.md](docs/BOARD.md).

## Paste this

```text
You are on Albion Native, the master repo. Read https://github.com/jxnplays/albion-native then docs/CATCHUP.md, docs/GAMES.md, docs/ISSUES.md, docs/HARDWARE.md, SECURITY.md, docs/PUBLISH.md.

1:1 means clone jxnplays/fable2rustybev and check out 6802309cc114e090d343a01c17832921084b35e3. Do not reimplement it.

Ask which Fable titles I own. Locate only those, per docs/GAMES.md. Do not copy an install into git.

If Fable 2 was the pick and it was found: cargo test --workspace, then cargo run -p fable2_game. Stay under 90% RAM and VRAM. Job is I-01 through I-04: one mesh, one texture, Bloodstone ground, one shot. Update the home-page row you moved.

A different model reviews the diff. If it works, publish in this session. Studio session: push. Anyone else: pull request. Do not push to jxnplays unless this session belongs to the studio head.
```

## What this is

| Piece | Rule | File |
|---|---|---|
| Ports | Pick one owned game. Fable 2 is the street. | [docs/GAMES.md](docs/GAMES.md) |
| Engine | Loads a port, then a second world, no second renderer. | [docs/LINEUP.md](docs/LINEUP.md) |
| Tools | Rename an NPC. Drop a GLB. Drive the exe. | [docs/NPCS.md](docs/NPCS.md), [docs/MODS.md](docs/MODS.md), [docs/RUNTIME.md](docs/RUNTIME.md) |
| Remaster | Waves, caustics, extra grass, extra NPCs. Off by default. | [docs/graphics/](docs/graphics/) |
| Remote | RustDesk unattended password, set on the PC, not in git. | [docs/REMOTE.md](docs/REMOTE.md) |
| Load | Under 90% of this machine's RAM and VRAM. | [docs/HARDWARE.md](docs/HARDWARE.md) |
| People | Studio head assigns seats. Sunday is two. | [docs/ROSTER.md](docs/ROSTER.md) |
| Publish | Working fix goes out the same session. | [docs/PUBLISH.md](docs/PUBLISH.md) |

## Sunday

| # | Need | Bar |
|---|---|---|
| 4 | One GLB in the scene | `░░░░░░░░░░` 0% |
| 5 | One texture on that mesh | `░░░░░░░░░░` 0% |
| 6 | Bloodstone ground | `░░░░░░░░░░` 0% |
| 9 | Shot of those three | `░░░░░░░░░░` 0% |

## Boot

| # | Chunk | Bar |
|---|---|---|
| 1 | Dump lists `default.xex` | `█░░░░░░░░░` 10% |
| 2 | Archive index | `████░░░░░░` 40% |
| 3 | Window titled Albion Native | `██████░░░░` 60% |

## Street

| # | Chunk | Bar |
|---|---|---|
| 4 | One GLB in the scene | `░░░░░░░░░░` 0% |
| 5 | One texture on that mesh | `░░░░░░░░░░` 0% |
| 6 | Heightfield drawn | `░░░░░░░░░░` 0% |
| 7 | One of 19,463 props placed | `░░░░░░░░░░` 0% |
| 8 | Collision | `░░░░░░░░░░` 0% |
| 9 | Shot | `░░░░░░░░░░` 0% |

## Formats

| # | Chunk | Bar |
|---|---|---|
| 10 | Models, 941 of 986 | `███████░░░` 70% |
| 11 | Foliage | `░░░░░░░░░░` 0% |
| 12 | Textures, ~100 of 1,339 | `██░░░░░░░░` 20% |
| 13 | Level records | `███░░░░░░░` 35% |
| 14 | Clips, curve mode wrong | `████░░░░░░` 40% |
| 15 | Lua extracted, none run | `███░░░░░░░` 30% |
| 16 | Audio extracted, none play | `██░░░░░░░░` 25% |

## Hero and town

| # | Chunk | Bar |
|---|---|---|
| 17 | Greybox body | `████░░░░░░` 40% |
| 18 | Idle, walk, run | `░░░░░░░░░░` 0% |
| 19 | Game mesh | `░░░░░░░░░░` 0% |
| 20 | Dog | `░░░░░░░░░░` 0% |
| 23 | One melee | `░░░░░░░░░░` 0% |
| 24 | One spell | `░░░░░░░░░░` 0% |
| 26 | First quest | `░░░░░░░░░░` 0% |
| 28 | One job | `░░░░░░░░░░` 0% |
| 35 | One cue | `░░░░░░░░░░` 0% |
| 36 | One save | `░░░░░░░░░░` 0% |

## Regions

| # | Chunk | Bar |
|---|---|---|
| 37 | Bloodstone data | `██░░░░░░░░` 15% |
| 38 | Market | `░░░░░░░░░░` 0% |
| 39 | Old Town | `░░░░░░░░░░` 0% |
| 40 | Bower Lake | `░░░░░░░░░░` 0% |
| 41 | Oakfield | `░░░░░░░░░░` 0% |
| 42 | Westcliff | `░░░░░░░░░░` 0% |
| 43 | Wraithmarsh | `░░░░░░░░░░` 0% |
| 44 | Knothole Island | `░░░░░░░░░░` 0% |
| 45 | See the Future | `░░░░░░░░░░` 0% |

## Tools and later worlds

| # | Chunk | Bar |
|---|---|---|
| 46 | NPC rename | `░░░░░░░░░░` 0% |
| 47 | Companion, mount, mob, prop drop | `░░░░░░░░░░` 0% |
| 48 | Drive the exe, see and hear it | `░░░░░░░░░░` 0% |
| 49 | RustDesk reopen without a new code | `░░░░░░░░░░` 0% |
| 50 | Asset manager | `░░░░░░░░░░` 0% |
| 51 | Water, caustics, extra grass | `░░░░░░░░░░` 0% |
| 53 | Fable 2 1:1 | `█░░░░░░░░░` 6% |
| 54 | Engine holds a second world | `░░░░░░░░░░` 0% |
| 55 | Fable 3 | `░░░░░░░░░░` 0% |
| 57 | Fable, TLC, Anniversary | `░░░░░░░░░░` 0% |
| 59 | Legends | `░░░░░░░░░░` 0% |

Issues I-01 through I-12: [docs/ISSUES.md](docs/ISSUES.md). I-01 through I-04 block Sunday.
