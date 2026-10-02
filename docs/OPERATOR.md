# Operator

A model told "pull this, build it as is" follows this order and stops. It does not invent a second engine.

## 1. Read

This repo is the master book, not the game crate.

1. `README.md` board.
2. `docs/ISSUES.md`.
3. `docs/REPOS.md`.
4. `SECURITY.md`.

## 2. Pull

```text
git clone https://github.com/jxnplays/albion-native.git
```

Code, if the studio head has granted access:

```text
git clone https://github.com/jxnplays/fable2rustybev.git
```

No other repo. `fable1rustybev`, `fable3rustybev`, and `fablelegendsrustybev` are not opened. Empty shells are ignored.

## 3. Build

In `fable2rustybev` only:

```text
cargo test --workspace
cargo run -p fable2_game
```

Set `FABLE2_DUMP` to a GOTY tree the operator owns. If it is unset, stop and write `BLOCKED`. Do not search the disk.

This book has no crate. Do not run cargo here.

## 4. Work

Take I-01 through I-04, or the row the studio head named. Update the board and the issue row in the same change. Proof is `docs/PROOF.md`.

## 5. Land

Fork. Pull request. Do not push to `jxnplays`. The studio head merges.
