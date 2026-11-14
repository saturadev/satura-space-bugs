**Bug reports and feature requests: [github.com/saturadev/satura-space-bugs](https://github.com/saturadev/satura-space-bugs)**

<h1 align="center">Satura Space — Issue Tracker</h1>

<p align="center">
  Bug reports and feature requests for <a href="https://saturaspace.com"><b>Satura Space</b></a>,<br/>
  the desktop app for running AI coding agents on a Unity project in parallel —<br/>
  and watching what they built, live, with no build step.
</p>

<p align="center">
  <a href="https://github.com/saturadev/satura-space-bugs/issues/new?template=bug_report.yml"><b>Report a bug</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/saturadev/satura-space-bugs/issues/new?template=feature_request.yml"><b>Request a feature</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/saturadev/satura-space-bugs/issues">Browse open issues</a>
  &nbsp;·&nbsp;
  <a href="https://saturaspace.com">Download</a>
</p>

---

## This repository has no code

Satura Space is closed source. This repo exists purely so bug reports and feature
requests live somewhere public — where you can see what's already been reported,
follow along, and add what you know. Everything happens in the
[Issues](https://github.com/saturadev/satura-space-bugs/issues) tab.

## Filing a good report

The single most useful thing you can give us is **a way to reproduce it**. After that:

- **Version and OS.** The **Report a bug** button inside the app fills these in for you — use it when you can.
- **Logs.** Attach them if the app misbehaved; they're usually the difference between a fix and a guess.
- **One issue per report.** Two bugs in one thread means one of them gets forgotten.

Before you file, [search existing issues](https://github.com/saturadev/satura-space-bugs/issues?q=is%3Aissue) —
if someone beat you to it, a 👍 and a comment with your details help more than a duplicate.

## Where the logs live

| Platform | Path |
|---|---|
| macOS | `~/Library/Logs/Satura Space/` |
| Windows | `%APPDATA%\Satura Space\logs\` |

Unity's own logs for a given agent are under that project's `.sspace/` directory.

Redact anything you'd rather not make public — logs can contain file paths and
project names, and issues here are visible to everyone.

## How issues are handled

| Label | Meaning |
|---|---|
| `needs triage` | Landed, not yet looked at. |
| `confirmed` | Reproduced on our side. |
| `needs info` | We can't act until you reply — stale ones get closed. |
| `in progress` | Being worked on right now. |
| `fixed` | Fixed in `main`, shipping in the next release. |
| `released` | Out in a public build. The issue closes here. |

## Security

Please **don't** open a public issue for a security vulnerability.
Use [private vulnerability reporting](https://github.com/saturadev/satura-space-bugs/security/advisories/new) instead.

## Account, billing, and licensing

Those aren't bugs and don't belong here — manage them at
[app.saturaspace.com](https://app.saturaspace.com).
If something there is genuinely broken, that *is* a bug: file it with the
**Account, billing & licensing** area selected.
