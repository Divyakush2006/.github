# Contributing

Thank you for taking the time to contribute. This guide applies to every repository owned by [@Divyakush2006](https://github.com/Divyakush2006) unless the repository has its own `CONTRIBUTING.md`.

## Ground rules

- Be respectful. Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- Never report a security vulnerability in a public issue. Follow the [security policy](SECURITY.md) instead.
- Keep each change focused: one bug fix or one feature per pull request.

## Reporting a bug

1. Search the existing issues to check it has not already been reported.
2. Open a new issue with the **Bug report** form and include:
   - what you expected to happen and what happened instead,
   - exact steps to reproduce it,
   - your environment (OS, runtime versions, browser where relevant),
   - logs or screenshots, with any secrets removed.

## Proposing a feature

Open an issue with the **Feature request** form before writing code. Describe the problem you want to solve rather than only the solution, so the approach can be agreed first.

## Making a change

1. Fork the repository and create a branch from the default branch:
   ```bash
   git checkout -b fix/short-description
   ```
   Use a prefix that matches the change: `feat/`, `fix/`, `docs/`, `refactor/`, `test/`, `chore/`.
2. Follow the setup steps in the repository's README.
3. Make your change, matching the existing code style and structure.
4. Add or update tests when behaviour changes, and run the existing test suite and linters before pushing.
5. Update the documentation when you change behaviour, configuration or public interfaces.

### Commit messages

Commits follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<optional scope>): <summary in the imperative mood>

<optional body explaining what changed and why>
```

Common types: `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.

Examples:

```
feat(api): add pagination to the search endpoint
fix(auth): reject expired refresh tokens
docs(readme): document the required environment variables
```

### Pull requests

1. Push your branch and open a pull request against the default branch.
2. Complete the pull request template: what changed, why, and how it was tested.
3. Make sure every CI check passes.
4. Respond to review feedback with new commits; they are squashed on merge.

## Licensing

By contributing, you agree that your contributions are licensed under the license of the repository you contribute to (see its `LICENSE` file).
