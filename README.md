<p align="center">
  <img src="docs/brand/mark.svg" alt="Albion Native. One Rust and Bevy engine for every Fable." width="880">
</p>

<p align="center">
  <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <img src="https://img.shields.io/badge/Bevy-runtime-c4a574?style=for-the-badge" alt="Bevy">
  <img src="https://img.shields.io/badge/work-ports%20%7C%20engine%20%7C%20tools-6b2d3c?style=for-the-badge" alt="Ports, engine, tools">
</p>

Three doors. Ports, the engine, and the tools. You and other people work one door at a time. Studio head: [jxnplays](https://github.com/jxnplays).

| Door | You get | Work here |
|---|---|---|
| Ports | Each Fable as a Rust and Bevy game. | `fable2rustybev` is the only tree with code. |
| Engine | One runtime that loads those ports and mixes assets you own. | This repo. Slices move here after a shot. |
| Tools | Rename an NPC, drop a Blender GLB, drive the window, browse a dump. | Contracts in `docs/NPCS.md`, `docs/MODS.md`, `docs/RUNTIME.md`. Not built. |

Map: [docs/WORK.md](docs/WORK.md).

## Paste this

```text
You are on Albion Native. Read https://github.com/jxnplays/albion-native then docs/WORK.md, docs/ISSUES.md, docs/OPERATOR.md, docs/HARDWARE.md, SECURITY.md, docs/PUBLISH.md.

Pick one door. Ports, engine, or tools. Do not open all three.

If the door is ports: code is jxnplays/fable2rustybev if you were given access. Do not open any other repo. If FABLE2_DUMP is unset, stop and write BLOCKED. cargo test --workspace, then cargo run -p fable2_game. Stay under 90% RAM and VRAM. Job is I-01 through I-04: one mesh, one texture, Bloodstone ground, one shot.

A different model reviews the diff. If it works, publish in this session. Studio session: push. Anyone else: pull request. Do not sit on a working fix. Do not push to jxnplays unless this session belongs to the studio head.
```

## Sunday

| Need | State |
|---|---|
| One converted mesh in the window | `░░░░░░░░░░` |
| One original texture on it | `░░░░░░░░░░` |
| Bloodstone ground under the body | `░░░░░░░░░░` |
| A shot of those three | `░░░░░░░░░░` |

## Board

| Chunk | Bar |
|---|---|
| Window opens | `██████░░░░` 60% |
| Models convert | `███████░░░` 70% |
| Textures convert | `██░░░░░░░░` 20% |
| Bloodstone parsed, not drawn | `███░░░░░░░` 35% |
| Fable 2 1:1 | `█░░░░░░░░░` 6% |
| Engine holds a second world | `░░░░░░░░░░` 0% |
| Tools | `░░░░░░░░░░` 0% |
