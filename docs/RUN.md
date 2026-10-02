# Run

Point a model at this file, then at a Fable 2 GOTY tree the operator already owns. The model does not hunt for discs, and it does not ask for one.

## Inputs

| Input | Where |
|---|---|
| Job | This repository. Read `VISION.md`, `STUDIO.md`, `docs/SEATS.md`, `docs/BACKLOG.md`, then this file. |
| Code | The private working tree `jxnplays/fable2rustybev`, until that code has been ported here. Do not start a second engine. |
| Game | Environment variable `FABLE2_DUMP`. It must contain `default.xex` and a `data/` directory. Title ID `4D5307F1`. |

If `FABLE2_DUMP` is unset, stop. Write `BLOCKED` and the missing variable name. Do not invent a path.

## Assignment

The studio head fills this before the model starts. A model that assigns itself is wrong.

```text
Department:
Builder:
Review:
Brief:
```

Builder and Review are different models. Review does not share the builder session.

## First proven slice

The job is not "port Fable 2." The job is the first open brief in `docs/BACKLOG.md` whose dependency is already true.

Current first slice: one converted model standing in the Bevy window, loaded through `FABLE2_DUMP`, with no game file committed.

Order under that slice:

1. Confirm the dump variable lists `default.xex` and the top-level archives.
2. Convert one non-foliage model to GLB under a local, gitignored output directory.
3. Load that GLB in the existing Bevy app.
4. Screenshot and a test that skips cleanly when the dump is absent.
5. Pull request against the brief. Review rejects game files, absolute paths, and status claims.

Do not start combat, a quest, or a second region in the same pass.

## Stop

Stop when the slice is in a pull request, or when a decoder disagrees with the file. A disagreement is a finding, not a reason to rewrite the runtime.

## What "just works" means

The model can begin without a tour. It cannot finish a 1:1 game in a pass. A 1:1 Fable 2 GOTY is the sum of the briefs in `docs/GOTY.md`, in the order in `ROADMAP.md`.
