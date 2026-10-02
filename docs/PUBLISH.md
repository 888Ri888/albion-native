# Publish

A fix that works is published in the same session. Holding a working diff is a failed job.

Proven means `docs/PROOF.md` is met: a test, or a shot, and no game file.

| Who | What they do |
|---|---|
| Studio head's own session | Push the proven diff to the working tree. Update the board on `albion-native` in the same session. |
| Anyone else | Open a pull request in the same session. Do not keep the patch local. Do not push to `jxnplays`. |

Review is the other model, before the push or the pull request. It checks the issue id, the board row, and `SECURITY.md`. A model does not approve its own diff.

Direct push to this account is the studio head's session only. That is what stops a stranger writing to the account. It is not permission to hide a fix.
