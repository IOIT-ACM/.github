# Contributing to IOIT ACM Projects

Thanks for your interest in contributing. This guide applies to all repositories under the IOIT ACM Student Chapter unless a repo has its own `CONTRIBUTING.md`, in which case that takes precedence.

## Getting started

1. Fork the repository and clone it locally.
2. Create a branch from `main` using the naming convention below.
3. Make your changes, commit, and push to your fork.
4. Open a pull request against `main` with a clear description of what you changed and why.

If you're unsure where to start, look for issues labeled `good first issue`.

## Branch naming

We use conventional branches: `<type>/<short-description>`, where `type` matches the commit types below.

```
feat/event-registration-form
fix/nav-overflow-mobile
docs/update-setup-guide
chore/update-dependencies
```

Keep descriptions lowercase and hyphen-separated.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/). Every commit message should be structured as:

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

**Types:**

| Type | Use for |
|------|---------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation changes only |
| `style` | Formatting, whitespace — no logic change |
| `refactor` | Code restructure with no feature or fix |
| `chore` | Build process, dependencies, tooling |
| `ci` | CI/CD configuration |
| `revert` | Reverting a previous commit |

**Examples:**

```
feat(events): add registration form with validation
fix: resolve nav overflow on mobile
docs: update local setup instructions
chore: bump typescript to 5.4
feat!: redesign ChapterOS dashboard  ← breaking change, use !
```

Keep the subject line under 72 characters and in the present tense: "add form" not "added form".

## Pull requests

- Keep PRs focused. One concern per PR makes review faster.
- Reference any related issue in the description (`closes #42`).
- Make sure the project builds and any existing tests pass before opening a PR.
- A maintainer will review and merge. If you don't hear back within a week, feel free to ping us.

## Questions

For questions about a specific repository, open an issue there. For anything else, reach us at [acm.studentbranch@aissmsioit.org](mailto:acm.studentbranch@aissmsioit.org).
