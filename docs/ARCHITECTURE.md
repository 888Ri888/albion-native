# Architecture

Albion Native is a workspace, not a script pile.

| Crate | Job |
|---|---|
| `albion_formats` | Read archives and records. No Bevy. |
| `albion_convert` | Turn decoded records into engine files. GLB, textures, clips. |
| `albion_game` | The Bevy runtime. Window, world, player, script host. |

The dump is an input. It is never a dependency of the build. Tests use synthetic fixtures in `fixtures/`.

The script host runs extracted behavior through a narrow API. It does not eval arbitrary files from the repo. World packs register content. They do not fork the runtime.

Public tree and private notes are different repositories. Paths, machine layout, and working logs stay out of this one.
