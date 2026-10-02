# Albion Native

Albion Native is my engine for Albion. One runtime, written in Rust and Bevy. Fable 2 GOTY is the first world. Later games are content on that same runtime, not separate ports glued together after the fact.

This repository is the production book. It is private until the studio head publishes it. It holds the design, the status, the seats, and the briefs. It does not hold game files, dump paths, or private notes.

Studio head: [jxnplays](https://github.com/jxnplays)

## What this is

A clean-room game engine, run like a production. Departments are in [STUDIO.md](STUDIO.md). The brain and the hive are in [docs/BRAIN.md](docs/BRAIN.md). Model seats are suggestions in [docs/SEATS.md](docs/SEATS.md). The studio head assigns them. A model does not choose its own department.

The player points the runtime at a Fable 2 GOTY install they already own. The engine reads that install and builds Albion in Bevy. The original executable is a reference for behavior. It is not the program being shipped.

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
| Fable 3, Fable TLC, Fable Legends | Named in the vision. Not this milestone. |

## Read next

1. [REVIEW.md](REVIEW.md) before this repository is made public.
2. [VISION.md](VISION.md) for the end state.
3. [STUDIO.md](STUDIO.md) for departments and who decides.
4. [docs/SEATS.md](docs/SEATS.md) before assigning a model.
5. [docs/BACKLOG.md](docs/BACKLOG.md) for the briefs.
6. [ROADMAP.md](ROADMAP.md) for the order of work.
7. [LEGAL.md](LEGAL.md) before you touch a dump.

## Help without guessing

Briefs are in [docs/BACKLOG.md](docs/BACKLOG.md). A pass does not start until the issue, or the brief, names the department, the builder, and a different model as review. Game files stay on the machine that owns the dump.
