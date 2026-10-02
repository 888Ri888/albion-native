# Games

The user picks the titles they own. A model locates only those. Missing titles are skipped, not errors.

| Pick | Variable | Needs |
|---|---|---|
| Fable 2 GOTY | `FABLE2_DUMP` | `default.xex` and `data/` |
| Fable 3 | `FABLE3_DUMP` | The owned install. Not opened as a port yet. |
| Fable or TLC | `FABLE1_DUMP` | The owned install. Not opened as a port yet. |
| Anniversary | `FABLE_ANNIVERSARY_DUMP` | Same quests as TLC. Not opened yet. |
| Legends | `FABLE_LEGENDS_DUMP` | Only if they have a legal source. |

## Locate

Ask which titles, or read the list they already gave. Search common install folders for those titles only. Set the variable. Do not scan for a game they did not name.

If the pick is Fable 2 and it is not found, write `BLOCKED` and the variable name. If the pick is Fable 3 and Fable 2 is absent, that is fine. Sunday work still needs Fable 2.

Never copy the install into git. Never locate a title to publish it.
