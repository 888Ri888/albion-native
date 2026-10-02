# Studio

Albion Native is run as a production, not as a chat. jxnplays is the studio head. Every other seat is assigned. A model does not pick its own job, and a contributor does not invent a department.

The brain is the written memory of the production: decisions, status, evidence, and open work. The hive is the set of models currently sitting in those seats. The repository is the only place a decision becomes real.

## Who decides

| Seat | Decides |
|---|---|
| Studio head (jxnplays) | Vision, milestone order, which model sits where, what merges. |
| Production | Turns the milestone into issues. Keeps status honest. |
| Department lead | The slice it was assigned. Nothing outside that slice. |
| Review | Rejects a change that has no evidence, no test, or a game file in it. |

If two seats disagree, the studio head decides. A model disagreement is not a creative vote.

## Departments

Same shape as a full Albion production. Empty seats stay empty until assigned.

| Department | Owns | Does not own |
|---|---|---|
| Engine | Bevy runtime, window, load, frame time | Quest text, map art |
| Tools | Archive decoders, converters, fixtures | Gameplay feel |
| World | Regions, heightfields, prop placement, roads | Combat numbers |
| Animation | Clips, skeletons, locomotion | Level data |
| Gameplay | Player, dog, combat, jobs, morality | Format parsers |
| Narrative | Lua quests, dialogue flow, script host | Rendering |
| Audio | Banks, playback, mix | Models |
| Presentation | Menu, HUD, time of day, lighting | Archive layout |
| QA | Reproduce, fixture, reject | New features |

## How a slice moves

1. Studio head assigns the department and the model.
2. The model reads the issue and the brain page for that department.
3. Work lands as a pull request that names the issue.
4. Review checks evidence, legal, and scope.
5. Studio head merges. Status changes only after the merge.

Outside help uses the same path. An open issue is the brief. A pull request is the delivery. A fork is not a second studio.
