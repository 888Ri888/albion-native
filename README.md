# Albion Native

<p align="left">
  <img src="docs/brand/mark.svg" alt="Albion Native" width="640">
</p>

<p align="left">
  <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <img src="https://img.shields.io/badge/Bevy-runtime-c4a574?style=for-the-badge" alt="Bevy">
  <img src="https://img.shields.io/badge/focus-Fable%202%20GOTY-6b2d3c?style=for-the-badge" alt="Fable 2 GOTY">
  <img src="https://img.shields.io/badge/status-private%20book-444444?style=for-the-badge" alt="Private book">
</p>

Master engine for Albion. The standalone ports stay their own games. This repo is where they join. Studio head: [jxnplays](https://github.com/jxnplays).

Official game art is not in this repo. The mark above is ours. A dump you own supplies the real frames.

## Repos

| Repo | Role |
|---|---|
| `albion-native` | Master. You are here. |
| `fable2rustybev` | Standalone Fable 2. Focus. Only tree with code. |
| `fable1rustybev` | Fable, TLC, Anniversary. Not opened. |
| `fable3rustybev` | Opens when Fable 2 is 1:1. |
| `fablelegendsrustybev` | Last. Legal source only. |

## Board

Agents update the row they moved. Rule: [docs/BOARD.md](docs/BOARD.md). Snapshot 2 October 2026.

### Boot

| Chunk | Bar |
|---|---|
| Dump lists `default.xex` | `█░░░░░░░░░` 10% |
| Archive index | `████░░░░░░` 40% |
| Window titled Albion Native | `██████░░░░` 60% |

### First street

| Chunk | Bar |
|---|---|
| One GLB in the scene | `░░░░░░░░░░` 0% |
| One texture on that mesh | `░░░░░░░░░░` 0% |
| Bloodstone ground | `░░░░░░░░░░` 0% |
| One prop placed | `░░░░░░░░░░` 0% |
| Collision on that ground | `░░░░░░░░░░` 0% |
| Shot of mesh, texture, ground | `░░░░░░░░░░` 0% |

Sunday is that shot. Not a 1:1.

### Formats

| Chunk | Bar |
|---|---|
| Model decoder | `███████░░░` 70% |
| Foliage sub-format | `░░░░░░░░░░` 0% |
| Texture decoder | `██░░░░░░░░` 20% |
| Level records | `███░░░░░░░` 35% |
| Animation clips | `████░░░░░░` 40% |
| Lua bytecode | `███░░░░░░░` 30% |
| Audio banks | `██░░░░░░░░` 25% |

### Hero and town

| Chunk | Bar |
|---|---|
| Greybox body | `████░░░░░░` 40% |
| Idle, walk, run on the body | `░░░░░░░░░░` 0% |
| Game mesh replaces greybox | `░░░░░░░░░░` 0% |
| Dog | `░░░░░░░░░░` 0% |
| Combat | `░░░░░░░░░░` 0% |
| First quest | `░░░░░░░░░░` 0% |
| Jobs, morality, HUD, audio, save | `░░░░░░░░░░` 5% |

### Later

| Chunk | Bar |
|---|---|
| Other regions and both packs | `░░░░░░░░░░` 0% |
| Agent tools and asset manager | `░░░░░░░░░░` 5% |
| Fable 2 1:1 | `█░░░░░░░░░` 6% |
| Fable 3, then the earlier games, then Legends | `░░░░░░░░░░` 0% |

## A model starts here

1. [docs/OPERATOR.md](docs/OPERATOR.md)
2. [docs/ROSTER.md](docs/ROSTER.md)
3. [docs/ISSUES.md](docs/ISSUES.md)
4. [SECURITY.md](SECURITY.md). Fork. Do not push to `jxnplays`.

[docs/graphics/](docs/graphics/) is the remaster layer. It does not replace the street.
