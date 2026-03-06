# Contributing to Kaelum

Thank you for your interest in contributing! Every contribution helps make the project better.

## Getting Started

1. **Fork** the repository you want to contribute to
2. **Clone** your fork locally
3. **Install** dependencies: `npm install`
4. **Run tests** to make sure everything works: `npm test`

## Development Workflow

1. Create a new branch from `main`:
   ```bash
   git checkout -b feat/your-feature
   ```
2. Make your changes
3. Write or update tests as needed
4. Run `npm test` to verify
5. Commit using [Conventional Commits](https://www.conventionalcommits.org/):
   ```bash
   git commit -m "feat(core): add new feature"
   ```
6. Push and open a Pull Request

## Commit Convention

We follow **Conventional Commits**:

| Prefix | Usage |
|--------|-------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation only |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `test` | Adding or updating tests |
| `chore` | Maintenance tasks |
| `perf` | Performance improvements |

## Pull Request Guidelines

- Describe **what** changed and **why**
- Reference related issues (e.g., `Closes #42`)
- Keep PRs focused — one feature or fix per PR
- Ensure all tests pass
- Update documentation if applicable

## Reporting Bugs

Use the Bug Report issue template. Include:

- Steps to reproduce
- Expected vs actual behavior
- Node.js version and package version
- Relevant logs or error messages

## Suggesting Features

Use the Feature Request issue template. Describe:

- The problem you're trying to solve
- Your proposed solution
- Any alternatives you considered

## Code of Conduct

All Kaelum repositories follow the [Contributor Covenant Code of Conduct](./CODE_OF_CONDUCT.md).
By participating, you agree to abide by its terms.
