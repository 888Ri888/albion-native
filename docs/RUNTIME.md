# Runtime seat

When a build produces the game executable, the assigned tester drives that window. A log is not a playtest. Realtime is the bar.

The tester is the lead, or a model the studio head named. An outside pull request does not get this seat, and it does not get the machine.

## It must be able to

- Launch the built executable, not a different binary.
- See the window. A shot after every action.
- Hear the window. One captured cue when audio is the bug.
- Send input as the player: menu keys, mouse, stick, confirm, back.
- Walk, look, and use. Controller state counts as feel. A rumble flag is enough until a device is assigned.
- Read the console from that same run.

## Loop

1. Launch.
2. Shot of the menu.
3. One input.
4. Shot of the result.
5. If the frame is wrong, file the issue id and stop. Do not stack fixes in the same minute.

## Not this seat

- ReShade is not required. The Vulkan loader already fails to open it, and the window still comes up.
- No dump path in the shot caption.
- No push to `jxnplays` from the test loop. The studio head merges.

The tools named in `docs/AGENT_TOOLS.md` are the in-world calls. This file is the window around them. Both are empty until the executable is the thing under test.
