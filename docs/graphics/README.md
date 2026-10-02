# Graphics

Port first. Remaster second. A water shader does not count as the first street.

The 1:1 bar is the original mesh, the original texture, and the original layout, loaded from a dump the operator owns. The remaster is a layer on top: caustics, waves, denser grass, more trees, more NPCs, and a settings menu. Both live in the Rust and Bevy build. Xenia and Fable 2 Recomp are oracles for how the original frame looks. They are not the renderer.

## Order

1. One converted mesh, one original texture, Bloodstone ground.
2. Bevy lights, shadows, and a day clock that match the region.
3. Settings menu, every toggle defaulting off except resolution.
4. Water, then grass, then extra trees, then extra NPCs.
5. Same stack on the master, so Fable 3 inherits it instead of growing a second renderer.

## Seats

| File | Job |
|---|---|
| [STACK.md](STACK.md) | Crates and references. Pin to the Bevy version in the working tree. |
| [SETTINGS.md](SETTINGS.md) | The menu. |
| [WATER.md](WATER.md) | Waves and caustics, after a lake exists. |
| [FOLIAGE.md](FOLIAGE.md) | Grass and trees. Original foliage decoder is still open. |
| [CROWD.md](CROWD.md) | Extra NPCs. Not a substitute for quest NPCs. |

A graphics pull request names the row on the home-page board. It does not raise the 1:1 row.
