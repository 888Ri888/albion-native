# Foliage

The original tree and grass format does not convert yet. That decoder is a 1:1 chunk. Extra grass is a remaster chunk. Do not mix them.

1:1: decode the foliage sub-format and place the original meshes.
Remaster: `bevy_feronia` cards on the heightfield, wind in the vertex shader, density from the settings menu. Extra trees are the same meshes instanced past the original prop table, tagged `remaster` so a 1:1 toggle hides them.
