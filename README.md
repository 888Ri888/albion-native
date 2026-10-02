# Albion Native

Albion Native is my engine for Albion. One runtime, written in Rust and Bevy. Fable 2 GOTY is the first rewrite and the thing that makes the engine real. Fable 3 starts when that rewrite is 1:1. The other Fable games join as world packs. The rewrites stay useful on their own.

This repository is the production book. It is private until the studio head publishes it. Running code stays in the private working tree until a slice is ported here. Game files never live in git.

Studio head: [jxnplays](https://github.com/jxnplays)

## Lineup

| Order | World |
|---|---|
| Now | Fable 2 GOTY, including Knothole Island and See the Future |
| When Fable 2 is 1:1 | Fable 3, then its packs |
| After Fable 3 is playable | Fable, The Lost Chapters, Anniversary as presentation on TLC |
| Last, legal source only | Fable Legends |

Detail is in [docs/LINEUP.md](docs/LINEUP.md).

## Point a model at the job

1. [docs/RUN.md](docs/RUN.md)
2. A dump you own, as `FABLE2_DUMP`
3. One chunk from [docs/SYSTEMS.md](docs/SYSTEMS.md) or one card from [docs/LORE.md](docs/LORE.md)
4. Chunk, department, builder, review

Another person's model uses the same contract: [docs/CONTRACT.md](docs/CONTRACT.md).

## What this is not

- Not a decompilation of an executable.
- Not an emulator.
- Not a strategy guide.
- Not a claim that any Fable already runs 1:1.
- Not a second studio under another name.

## Status

Honest snapshot, 2 October 2026. Detail in [STATUS.md](STATUS.md).

| Layer | State |
|---|---|
| Engine decision | Locked. Rust + Bevy. Clean-room. |
| Fable 2 formats | In progress. Bloodstone parses. Town is not drawn. |
| Quest cards | Indexed. None running. |
| Asset manager | Required. Not in this repo yet. |
| Fable 3 and the rest | Named. Blocked on the Fable 2 1:1 bar. |

## Read next

1. [REVIEW.md](REVIEW.md) before this is public.
2. [docs/LINEUP.md](docs/LINEUP.md) for the merge.
3. [docs/RUN.md](docs/RUN.md) to start a model.
4. [docs/SYSTEMS.md](docs/SYSTEMS.md) and [docs/LORE.md](docs/LORE.md) to take a chunk.
5. [docs/ASSET_MANAGER.md](docs/ASSET_MANAGER.md) for the tool that is still to be added.
6. [LEGAL.md](LEGAL.md) before anyone touches a dump.
