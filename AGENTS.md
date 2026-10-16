# AGENTS.md — Niagara-Issues

The public GitHub home of Niagara Launcher: the `README.md` landing page and the
[releases](https://github.com/NiagaraLauncher/Niagara-Issues/releases), each of which carries the
release APK. Feature requests and bug reports have moved to
[feedback.niagaralauncher.com](https://feedback.niagaralauncher.com/); opening new issues here is
switched off, and `.github/ISSUE_TEMPLATE/config.yml` links to the feedback board instead. Older issues
remain in the tracker.

**This repo is public.** Everything committed, and every issue comment, label or release change, is
world-readable. Don't comment on, close or relabel issues, and don't create, edit or delete releases or
tags, without explicit confirmation — releases are published by an automated account, not by hand.

## Layout

| Path | What it is |
|---|---|
| `README.md` | Landing page: where to send feedback, release and download links |
| `.github/ISSUE_TEMPLATE/config.yml` | Disables blank issues; links "Request a feature" and "Report a bug" to the feedback board |

There is no code, build or CI here.

## Commit messages

Every commit message starts with a Gitmoji and follows the org-wide guide in [`GITMOJI.md`](https://github.com/NiagaraLauncher/NiagaraUmbrella/blob/main/GITMOJI.md) of the NiagaraUmbrella workspace repo — the format, the emoji list, and the standard conventions live there. When this repo is cloned inside the umbrella workspace, the guide is at `../GITMOJI.md`.

Do not add a "Co-Authored-By: Claude" note (or any similar co-authored-by trailer) to commit messages.

## Git

- The default branch of `NiagaraLauncher/Niagara-Issues` is `master`. Nothing is pushed or force-pushed
  to it without explicit confirmation; changes go through a branch and a pull request.
