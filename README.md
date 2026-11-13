# .github

Default community health files and the organisation profile for
[`nonagenticai`](https://github.com/nonagenticai).

GitHub applies these files to every repository in the organisation that does not define its
own copy. A repository's own file always wins.

| Path | Applies as |
|---|---|
| `SECURITY.md` | Security policy |
| `CONTRIBUTING.md` | Contribution guide |
| `CODE_OF_CONDUCT.md` | Code of conduct |
| `SUPPORT.md` | "Where to get help" |
| `.github/PULL_REQUEST_TEMPLATE.md` | Pull request template |
| `profile/README.md` | The organisation landing page |
| `.github/ISSUE_TEMPLATE/*` | **Not inherited** — copy these into a repository that wants them |

Measured 2026-11-13: GitHub inherits SECURITY, CONTRIBUTING, CODE_OF_CONDUCT, SUPPORT and
the pull request template, but **not** issue templates. The files here under
`.github/ISSUE_TEMPLATE/` are the canonical source to copy into a repository.

## Changing these files

These files apply to every public repository in the organisation at once. Open an issue
before changing anything here, and expect the change to be reviewed as an organisation-wide
policy change rather than a docs edit.

## License

Apache-2.0 — see [`LICENSE`](LICENSE).
