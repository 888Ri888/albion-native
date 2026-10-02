# Games

The user picks the titles they own. A model searches the disk for the original files of those titles only. A title they did not name is not searched. A title that is not found is skipped, not a failure, except Fable 2 when that was the pick.

## What to find

| Pick | Variable | Original files |
|---|---|---|
| Fable 2 GOTY | `FABLE2_DUMP` | `default.xex` (title `4D5307F1`) and a `data/` directory of BNK archives. An extracted dump counts. A disc image alone does not. |
| Fable 3 | `FABLE3_DUMP` | The owned install: PC `Fable3.exe` plus its data tree, or a 360 extract with `default.xex`. |
| Fable or TLC | `FABLE1_DUMP` | The owned install. `Fable.exe` or the TLC data tree. |
| Anniversary | `FABLE_ANNIVERSARY_DUMP` | The owned PC install. Same quests as TLC, later build. |
| Legends | `FABLE_LEGENDS_DUMP` | Only a legal source they already have. Do not hunt a retail disc. There was not one. |

## Where to look

For each picked title, search these roots and stop at the first tree that has the files above.

- The variable, if it is already set.
- Steam `steamapps/common`.
- Xbox app and extracted-ISO folders the user named.
- `Games`, `Dumps`, and `ROMs` under the user profile and on secondary drives.

Do not scan the whole disk if those roots miss. Ask for the folder. Do not copy the install into git. Do not search for a game they did not pick.

Sunday still needs Fable 2. Fable 3 alone is a valid pick for later. It does not unblock the street.
