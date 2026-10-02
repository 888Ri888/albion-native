# Water

Blocked until a street has a water plane. Bloodstone harbor is the first body, not an open ocean.

Pass 1: flat plane, original color, no shader.
Pass 2: `bevy_water` height, normals, objects sampling wave height.
Pass 3: caustics on the bed, faded by depth, aligned to the sun.
Pass 4: shoreline foam and a refraction sample. One sample. Full-screen refraction is a known frame drop.

Per body later: ocean, lake, pond. Albion does not need an FFT ocean to clear the Sunday bar.
