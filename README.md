# Albion Native

Albion Native is my engine for Albion. One runtime, written in Rust and Bevy. Fable 2 GOTY is the first world, and it is the world that forces the engine to be real. Later games are content packs on that runtime.

This repository is the production book. It is private until the studio head publishes it. The running code still lives in the private working tree until a slice is ported here. Game files never live in either repository.

Studio head: [jxnplays](https://github.com/jxnplays)

## Point a model at the job

1. This repository, starting at [docs/RUN.md](docs/RUN.md).
2. A Fable 2 GOTY tree the operator owns, as `FABLE2_DUMP`.
3. One chunk from [docs/SYSTEMS.md](docs/SYSTEMS.md) or one card from [docs/LORE.md](docs/LORE.md).
4. An assignment: chunk, department, builder, review.

Claude, LongCat, or another model can take the chunk. The merge rules are [docs/CONTRACT.md](docs/CONTRACT.md). The model does not invent a second architecture inside the chunk.

## What this is

A clean-room game engine, run like a production. Departments are in [STUDIO.md](STUDIO.md). Systems are in [docs/SYSTEMS.md](docs/SYSTEMS.md). Quest and world cards are in [docs/LORE.md](docs/LORE.md). The 1:1 map is [docs/GOTY.md](docs/GOTY.md).

The original executable is a reference for behavior. It is not the program being shipped.

## What this is not

- Not a decompilation of `default.xex`.
- Not an emulator.
- Not a strategy guide. Cards are one line, not walkthroughs.
- Not a claim that Fable 2 GOTY already runs 1:1.

## Status

Honest snapshot, 2 October 2026. Detail in [STATUS.md](STATUS.md).

| Layer | State |
|---|---|
| Engine decision | Locked. Rust + Bevy. Clean-room. |
| Archive formats | In progress. |
| Quest cards | Indexed. None running. |
| Bloodstone | Data parses. Not drawn. |
| Playable runtime | Window, menu, greybox player. |
| Later games | Named. Blocked on the Fable 2 spine. |

## Read next

1. [REVIEW.md](REVIEW.md) before this repository is made public.
2. [docs/RUN.md](docs/RUN.md) to start a model.
3. [docs/SYSTEMS.md](docs/SYSTEMS.md) to pick a section.
4. [docs/LORE.md](docs/LORE.md) to pick a card.
5. [docs/CONTRACT.md](docs/CONTRACT.md) before two models work at once.
6. [LEGAL.md](LEGAL.md) before anyone touches a dump.
