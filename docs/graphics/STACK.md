# Stack

Pin every crate to the Bevy version already in `fable2rustybev`. Do not bump Bevy to chase a shader.

| Need | Use | Note |
|---|---|---|
| Waves, tileable ocean, wave-height query | `bevy_water` | Gerstner-style height. Caustics are not in the crate. |
| FFT or analytic ocean, foam, shallow optics, caustics toggle | `bevy-aqua` | Bevy 0.19. Do not adopt it until the working tree is on that version. |
| Caustic projection aligned to the sun | Custom WGSL, after `bevy_water` | Pattern is a projected sine and Voronoi, faded by depth. |
| Grass scatter and wind | `bevy_feronia` | Instanced cards. Density is a setting. |
| Simpler grass instance field | `bevy_procedural_grass` | Older Bevy. Reference only unless it builds. |
| Sky, TAA, bloom, volumetric fog, SSR | Bevy `atmosphere` example | Built in. No third crate required. |
| Original frame at 2x | GummiFableII Xenia presets, just-harry femtofork | Oracle for hero and dog texture bugs. Not linked into the build. |
| Hero and dog texture oracle | himdo/Fable-2-Recomp 1.3 notes | Same bug class. Do not ship the recomp. |

WGSL lives under `assets/shaders/` in the working tree when a pass needs a custom file. The book does not vendor shader source.
