# NPCs

Quest NPCs come from the scripts. Extra townsfolk are the density slider in `docs/graphics/CROWD.md`. Names are a third category.

## Name overrides

A local file, not committed, maps a game id to a display string. The script id does not change. Only the label the player sees.

```text
dog = "name"
blacksmith_oakfield = "name"
```

The dog is a valid row. So is any named NPC. An empty file means the original names. A missing id means the original name. No override is pushed to git, and no override is published.

This does not change quest logic, voice lines, or who the dog follows.
