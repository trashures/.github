# Contributing

Thanks for helping. Trashures is a small project, so the rules are short.

## Workflow

1. Open or pick an issue first, so work is not done twice.
2. Work on a branch; `main` is protected (no direct or force push, the `checks` job must be green).
3. Open a pull request. PRs are **squash merged**, so the PR title becomes the commit message.

## PR titles: Conventional Commits

Versions and release notes are generated from the PR title, so it must follow
[Conventional Commits](https://www.conventionalcommits.org):

| Type | Use for | Release |
|---|---|---|
| `feat:` | new user-facing behaviour | minor |
| `fix:` | bug fix | patch |
| `perf:` | performance | patch |
| `docs:`, `test:`, `refactor:`, `style:`, `build:`, `ci:`, `chore:` | everything else | none |
| `infra:` | infrastructure (`infra/**`) | none |
| `deploy:` | overlays, rolling out | none |

Use `infra:` instead of `feat(infra):`. Mark breaking changes with `!` (`feat!: ...`).

## Changes

- Every behaviour change gets a unit test. Unit tests run without network: mock external APIs
  and model calls.
- Rule data needs the official source URL for every rule.
- Never commit secrets or `.env` files. Stage files explicitly instead of `git add -A`.
- User-facing German text contains no em dashes.

Repo-specific setup and commands are in each repo's `README.md`.
