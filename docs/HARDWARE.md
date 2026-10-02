# Hardware

A model reads the machine it is on before a heavy job. It does not assume a server.

Default if the probe fails: 16 to 32 GB system RAM, one discrete GPU, no extra card. This studio PC, from the 1 October boot log, is an i7-10700F, 32 GB RAM, and an AMD Radeon RX 6700 XT. Re-read the live box. Do not trust this sentence after a hardware change.

## Cap

Stay under 90% of installed RAM and under 90% of that GPU's VRAM. Leave the last 10% for Windows. A job that would cross the line is split or killed.

No hard lockout. No driver reset. No full-screen mode that cannot be alt-tabbed. One game executable at a time. Batch converts run in chunks, not 986 models in one process if the probe says memory is already high.

## Probe

Before `cargo run` or a batch convert, record total RAM, used RAM, GPU name, and VRAM. If used RAM is already over 80%, do not start the batch. Write `BLOCKED` and the numbers.
