# trashures/.github

Org-wide defaults for [github.com/trashures](https://github.com/trashures).

| Path | Effect |
|---|---|
| [`profile/README.md`](profile/README.md) | Public org profile on github.com/trashures |
| [`CONTRIBUTING.md`](CONTRIBUTING.md), [`SECURITY.md`](SECURITY.md), [`SUPPORT.md`](SUPPORT.md), [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Default community health files for every repo without its own copy |
| [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE/), [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | Default issue forms and PR template |
| [`FUNDING.yml`](FUNDING.yml) | Default sponsor button |
| [`workflow-templates/`](workflow-templates/) | Starter workflows under "Actions > New workflow" |

A file in a repo always wins over the default here. Issue templates are all or nothing: a repo
with its own `.github/ISSUE_TEMPLATE/` folder ignores every template from this repo.

Keep this repo free of secrets and internal details: it is public so that the defaults apply.
Internal documentation lives in [trashures/handbook](https://github.com/trashures/handbook).

The templates and texts in this repo are [MIT](LICENSE) licensed. A licence here does not apply to
other repos: each repo carries its own `LICENSE` (code in trashures/trashures is AGPL-3.0-or-later).
