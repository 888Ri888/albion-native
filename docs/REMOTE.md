# Remote

The studio head can see the window, hear it, and send a command from a phone, a Mac, an Android, or a laptop. The home PC stays the machine that runs the build.

RustDesk is the door. The one-time password is why the session dies. Turn on unattended access and set a permanent password in the RustDesk client on the home PC. That password is not written here, not committed, and not sent to a model.

## Home PC

- RustDesk installed and left open.
- Unattended access on.
- Permanent password set in the client. Store it in a password manager, not in this repo.
- Windows sleep off while a session is expected. A sleeping PC looks like a timeout.
- The game executable is already running, or one click from the desktop, before the phone connects.

## Phone or laptop

- Same RustDesk account, or the home PC id plus the permanent password.
- Close the mobile view. Reopen it. The permanent password must still work. If RustDesk asks for a new one-time code, unattended access is off.

## Commands

The remote view is the window in `docs/RUNTIME.md`. Typing in that view is player input. A build command still happens on the home PC. A model does not get the RustDesk password.

## If RustDesk drops

Tailscale to the home PC is the backup, already used for other sessions. Do not open the game port on the router. Do not put the permanent password in a chat log.
