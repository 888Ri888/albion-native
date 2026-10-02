# Cross-model contract

LongCat, Claude, or any other model can take a chunk. The repository is the merge. The model is not.

## Before starting

Write on the brief:

```text
Chunk:
Department:
Builder:
Review:
```

Review is a different model, or the studio head. The builder does not approve its own card.

## While working

- Edit the chunk you named. Do not reformat a file you do not own.
- Use the card shape in [LORE.md](LORE.md).
- Do not commit game files, dialogue dumps, or absolute paths.
- If your model wants a different architecture, stop. Open a question. Do not land it inside a quest chunk.

## Landing

The pull request title is the chunk ID. The body says what changed, what was not tested, and which card moved status. Two models on two chunks must not touch the same lines. If they do, the later pull request rebases. It does not rewrite the other chunk.
