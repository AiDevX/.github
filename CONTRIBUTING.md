# Contributing to AiDevX

Thank you for helping! This guide applies to every repository in the AiDevX organization. A project can add its own rules in its own `CONTRIBUTING.md`.

## Ways to help

- **Report a bug** or **suggest a feature**: open an issue in the project's repository. Search first to avoid duplicates.
- **Fix wrong data**: every directory page has a "Fix it" link. Small corrections are the most useful contributions.
- **Send code or docs**: open a pull request (see below).
- **Ask a question or share an idea**: use [Discussions](https://github.com/orgs/aidevx/discussions).

## Pull requests

1. For anything bigger than a small fix, open an issue first so we can agree on the approach.
2. Fork the repository and create a branch from `main`.
3. Keep the change focused: one topic per pull request.
4. Make sure the project's checks pass (lint, tests, build).
5. Describe **what** you changed and **why**. Add screenshots for UI changes.

We try to reply to every pull request within a few days.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
feat(directory): add framework filter
fix(collector): handle renamed repositories
docs: explain the health score
```

## Rules for data

In data projects such as the AI Dev Tools Directory:

- Humans decide **what is listed** and **in which category**.
- Numbers such as stars, commits, releases, license and health are **never edited by hand**. The collector script writes them.
- Paid placement never changes rankings or health data.

## Code of conduct

Everyone taking part must follow our [Code of Conduct](./CODE_OF_CONDUCT.md). Be kind and assume good intent.

## License

By contributing, you agree that your contribution is licensed under the license of the repository you contribute to.
