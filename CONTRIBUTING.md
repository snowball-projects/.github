# Contributing to snowball

snowball is founder-led. Nas Delevski sets product direction and makes the final
call on scope. Contributions may be welcome, but a working pull request is not
an agreement to merge it.

Some repositories add their own `CONTRIBUTING.md` with rules specific to their
data, interfaces or checks. Where one exists, it takes precedence over this
file.

## Before opening a pull request

Open an issue first for anything that changes an interface, a public claim, a
data source, a dependency or the project's scope. Small fixes with an obvious
correct answer — a broken link, a failing check, a typo — do not need one.

## What a pull request should contain

- The problem it solves, the decisions that mattered, and how you verified the
  result.
- The repository's own checks, run and passing. Each `README.md` documents them.
- No new dependency, service or infrastructure without a demonstrated need.
- No credentials, private data or personal locations, in the diff or in logs.

## Data and licensing

snowball's own software is MIT licensed. Third-party data, media and
dependencies keep their own terms, recorded in each repository's
`THIRD-PARTY-NOTICES.md`. A contribution must not extend snowball's license to
material it does not own, and must preserve existing attribution.

By contributing you agree your work is licensed under the repository's license.

## Reporting a vulnerability

See [SECURITY.md](SECURITY.md). Do not open a public issue for one.
