<p align="center">
  <img src="docs/brand/mark.svg" alt="Albion Native. One Rust and Bevy engine for every Fable." width="880">
</p>

<p align="center">
  <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <img src="https://img.shields.io/badge/Bevy-runtime-c4a574?style=for-the-badge" alt="Bevy">
  <img src="https://img.shields.io/badge/work-ports%20%7C%20engine%20%7C%20tools-6b2d3c?style=for-the-badge" alt="Ports, engine, tools">
</p>

This is the master repo. The Fable 2 build is `fable2rustybev` at commit `6802309`. Catch up there. Do not start a second port. Studio head: [jxnplays](https://github.com/jxnplays).

| Door | You get | Work here |
|---|---|---|
| Ports | Each Fable as a Rust and Bevy game. Pick one. | [docs/CATCHUP.md](docs/CATCHUP.md), then `fable2rustybev`. |
| Engine | One runtime that loads those ports. | This repo. Slices move here after a shot. |
| Tools | Rename an NPC, drop a GLB, drive the window. | `docs/NPCS.md`, `docs/MODS.md`, `docs/RUNTIME.md`. Not built. |

Games you own: [docs/GAMES.md](docs/GAMES.md).

## Paste this

```text
You are on Albion Native, the master repo. Read https://github.com/jxnplays/albion-native then docs/CATCHUP.md, docs/GAMES.md, docs/ISSUES.md, docs/HARDWARE.md, SECURITY.md, docs/PUBLISH.md.

1:1 means clone jxnplays/fable2rustybev and check out 6802309cc114e090d343a01c17832921084b35e3. Do not reimplement it. Do not open any other port repo.

Ask which Fable titles I own. Locate only those, per docs/GAMES.md. Do not copy an install into git.

If Fable 2 was the pick and it was found: cargo test --workspace, then cargo run -p fable2_game. Stay under 90% RAM and VRAM. Job is I-01 through I-04: one mesh, one texture, Bloodstone ground, one shot.

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
