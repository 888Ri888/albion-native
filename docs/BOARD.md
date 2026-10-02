# Board rule

The scoreboard is the table at the top of `README.md`. It is the public status. `STATUS.md` does not override it.

A model that moves a chunk updates that row in the same pull request. No separate status pass.

## When you edit the board

- The row you finished, or partly finished, changes percent.
- The "why" cell says what the pull request proved.
- You do not raise a row you did not touch.
- You do not lower a row to look careful. You lower it if the old number was false.

## Percents

| Move | Only if |
|---|---|
| 0 to 25 | A fixture or a local dump run exists, and the note names it. |
| 25 to 50 | It runs in the Bevy window, shot linked. |
| 50 to 75 | It survives a reload. |
| 75 to 100 | The chunk's done line in `docs/SYSTEMS.md` is true. |

Review rejects the pull request if the code changed and the board did not.
