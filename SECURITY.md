# Security

This repository holds no tokens, passwords, deploy keys, or workflows. Do not add them.

A model told to pull and build does not receive write access to `jxnplays`. It clones, builds, and opens a pull request from a fork. It does not run `git push` against `github.com/jxnplays/albion-native` or any other repo under that account.

Forbidden in a commit:

- A personal access token, a GitHub app key, or a `.env` with credentials.
- A workflow with `permissions: write` or a push to another repository.
- A machine path, a dump, or a derived game file.

If a session already has the studio head's credentials, it still does not push unless that session was opened by the studio head for a merge. An outside model never meets that test.
