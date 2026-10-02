# Catch up

1:1 means this tree, not a rewrite. A model that starts a new crate has left the job.

## Minimum

```text
git clone https://github.com/jxnplays/fable2rustybev.git
cd fable2rustybev
git checkout 6802309cc114e090d343a01c17832921084b35e3
```

That commit is the build. Access is required. This book does not contain it.

Read `docs/STATE.md` and `docs/brain/`. Ignore `PROGRESS.md` if it says 55%. The board in `albion-native` wins. Ignore `crates/fable2_game/bak/`. It was parked so the crate would compile. It is not the running game.

Then:

```text
cargo test --workspace
cargo run -p fable2_game
```

Stay under 90% RAM and VRAM. Locate only the games in `docs/GAMES.md`.

## What that build already has

- A window titled Albion Native and a greybox body.
- An MDL to GLB converter. 941 of 986 models convert. Foliage does not.
- Bloodstone level data parsed, about 19,463 instances, not drawn.
- About 100 of 1,339 textures converted, none applied.
- 4,082 animation clips mapped. Curve mode is wrong. None play.
- Lua and audio extracted. None run.

## Next

I-01 through I-04 only. One mesh, one texture, Bloodstone ground, one shot. Do not redo the converter.
