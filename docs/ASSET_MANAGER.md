# Asset manager

The studio head has a separate asset manager. It is not in this repository yet. It is a required seat on the engine, not a side toy.

When it is added, it is the only tool that browses a local owned install. The game crates do not grow their own browsers.

## Job

- Point at `FABLE2_DUMP`, and later at one variable per world.
- List archives, models, textures, levels, clips, scripts, and audio without copying them into git.
- Hand a chosen record to the converter.
- Stay useful to other projects. The manager is not Fable-only. Fable is the first client.

## Not yet

No path, no binary, and no claim that the manager already drives the Bevy scene. A pull request that vendors the tool says so in the title and strips machine paths.

Until that pull request, decoders in the working tree are the browser.
