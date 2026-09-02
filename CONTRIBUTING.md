# Contributing to Salt.Box

Thanks for your interest in Salt.Box!

## Where development happens

The repositories in this GitHub organization are **read-only mirrors**. All
active development, issue tracking, and merge requests for Salt.Box happen on
our primary GitLab instance:

- **GitLab**: <https://dev.saltbox.pro/>
- **Browse all projects**: <https://dev.saltbox.pro/explore/projects?sort=latest_activity_desc>

> **NOTE:** Issues and pull requests opened here on GitHub are **NOT** reviewed – please use
GitLab instead, or one of the channels below

## Reporting bugs and requesting features

- Open an issue on the relevant project's GitLab page
- Message us on [Telegram](https://t.me/salt_box/)
- Email [info@saltbox.pro](mailto:info@saltbox.pro)

> **ATTENTION:**
>
> For security vulnerabilities, do **NOT** open a public issue – see
[`SECURITY.md`](./SECURITY.md) instead

## Working with the code

Each repository documents its own setup, dependencies, and test commands in
its `README.md` (and, where present, its own `CONTRIBUTING.md` with more
specific rules, e.g. branch naming or the changelog format). Most Python
services in the Salt.Box stack use [`uv`](https://docs.astral.sh/uv/) for
environments, [pytest](https://docs.pytest.org/) for tests,
[ruff](https://astral.sh/ruff) for linting/formatting,
[mypy](https://mypy.readthedocs.io/) for static type checking, and
[pre-commit](https://pre-commit.com/) for Git hooks – check the repository
you're interested in for the exact commands.

## Commit messages

Keep the commit header short and imperative (e.g. "Add X", "Fix Y"), with an
optional body for non-obvious changes. [How to Write a Git Commit
Message](https://cbea.ms/git-commit/) is a good general reference.
