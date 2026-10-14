# Contributing to CircleXO

> This is the default guide for every repository in the CircleXO organization. A repository
> with its own `CONTRIBUTING.md` overrides it; read that one first.

Thanks for wanting to help. This guide covers how to get a local setup running, the conventions
the codebase follows, and how a change gets merged.

## Ways to contribute

- Report a bug or request a feature through the [issue forms](the **Issues** tab of the repository the problem is in).
- Pick up an issue labelled [`good first issue`](https://github.com/issues?q=is%3Aopen+org%3Acirclexo+label%3A%22good+first+issue%22)
  or [`help wanted`](https://github.com/issues?q=is%3Aopen+org%3Acirclexo+label%3A%22help+wanted%22). Comment on it first so nobody
  duplicates the work.
- Improve the docs. Typos and unclear sentences are worth a PR.

Security problems are **not** issues. Follow [SECURITY.md](SECURITY.md) instead.

## Local setup

Each repository's README explains how to build and run it. Clone the repository you want to work on and follow its README.

## Before you open a pull request

Run the repository's own tests and linters before opening a pull request; CI runs the same checks.

## Conventions

- **Small, focused PRs.** One concern per PR; refactors separate from behaviour changes.
- **Branch names:** `feat/…`, `fix/…`, `docs/…`, `chore/…` off the default branch.
- **Commit messages:** [Conventional Commits](https://www.conventionalcommits.org/) style
  (`feat: …`, `fix: …`, `docs: …`), imperative mood, explain *why* in the body.
- **Tests:** a bug fix comes with a test that fails without it; a feature comes with tests for its
  main path and its permission checks.
- **No secrets** in code, tests, fixtures or screenshots. Configuration goes in `.env`
  (documented in `.env.example`).
- **AI-assisted contributions are welcome.** Agents should read the repository's `AGENTS.md`. You are
  responsible for every line you submit: review it, run it, and test it as if you wrote it.

## Developer Certificate of Origin (DCO)

Every commit must be signed off, certifying the [Developer Certificate of Origin](https://developercertificate.org/):
you wrote the change, or otherwise have the right to submit it under the project's license.

```bash
git commit -s -m "fix: describe the change"
```

This adds a `Signed-off-by: Your Name <you@example.com>` trailer that matches your Git identity.
Forgot? `git commit --amend -s` for the last commit, or `git rebase --signoff <default-branch>` for a branch.

## License

Unless a repository's `LICENSE` says otherwise, CircleXO projects are licensed under the
[GNU AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html). By contributing you agree your contribution is
licensed under the license of the repository you contribute to.

## Community

- **Questions and ideas:** [GitHub Discussions](https://github.com/circlexo/.github/discussions)
- **Bugs and feature requests:** [Issues](the **Issues** tab of the repository the problem is in)

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
