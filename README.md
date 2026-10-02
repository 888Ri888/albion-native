# Albion Native

Albion Native is my engine for Albion. One runtime, written in Rust and Bevy. Fable 2 GOTY is the first world, and it is the world that forces the engine to be real. Later games are content packs on that runtime.

This repository is the production book. It is private until the studio head publishes it. The running code still lives in the private working tree until a slice is ported here. Game files never live in either repository.

Studio head: [jxnplays](https://github.com/jxnplays)

## Point a model at the job

1. This repository, starting at [docs/RUN.md](docs/RUN.md).
2. A Fable 2 GOTY tree the operator owns, as `FABLE2_DUMP`.
3. An assignment: department, builder, review, brief.

The model then takes the first open brief. It does not invent a second engine, and it does not jump to Fable 3.

## What this is

A clean-room game engine, run like a production. Departments are in [STUDIO.md](STUDIO.md). The brain and the hive are in [docs/BRAIN.md](docs/BRAIN.md). Seats are in [docs/SEATS.md](docs/SEATS.md). The 1:1 map is [docs/GOTY.md](docs/GOTY.md). The later-world contract is [docs/ENGINE.md](docs/ENGINE.md).

The original executable is a reference for behavior. It is not the program being shipped.

## What this is not

- Not a decompilation of `default.xex`.
- Not an emulator.
- Not a place for ripped models, audio, or discs.
- Not a claim that Fable 2 GOTY already runs 1:1.
- Not a second studio under another name.

## Status

Honest snapshot, 2 October 2026. Detail in [STATUS.md](STATUS.md).

| Layer | State |
|---|---|
| Engine decision | Locked. Rust + Bevy. Clean-room. |
| Archive formats | In progress. Models, textures, levels, animation, scripts, and audio have working decoders. |
| Model conversion | 941 of 986 models convert. Foliage format is still open. |
| Textures | Extracted. Conversion is early. |
| Bloodstone | Level data parses. It is not a rendered town yet. |
| Playable runtime | A native window, a menu, and a greybox player. |
| Quests, jobs, morality, DLC | Not started. |
| Fable 3, Fable TLC, Fable Legends | Named. Blocked on the Fable 2 spine. |

## Read next

1. [REVIEW.md](REVIEW.md) before this repository is made public.
2. [docs/RUN.md](docs/RUN.md) to start a model.
3. [docs/GOTY.md](docs/GOTY.md) for the 1:1 map.
4. [docs/ENGINE.md](docs/ENGINE.md) for later worlds.
5. [STUDIO.md](STUDIO.md) and [docs/SEATS.md](docs/SEATS.md) before assigning a model.
6. [LEGAL.md](LEGAL.md) before anyone touches a dump.
