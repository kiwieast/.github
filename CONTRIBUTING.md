# Contributing

## Commit messages

Every commit uses [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <short description>
```

- **type**: category of change (table below)
- **scope** (optional): affected part, e.g. `web`, `api`, `setup`, `research`
- **description**: short, imperative, lowercase, no period

| Type | Purpose | Example |
|---|---|---|
| `feat` | New feature | `feat(auth): add login endpoint` |
| `fix` | Bug fix | `fix(api): handle null responses` |
| `docs` | Documentation only | `docs(setup): add email routing steps` |
| `style` | Formatting, no logic change | `style: format source files` |
| `refactor` | Restructure, no behavior change | `refactor: simplify validation logic` |
| `perf` | Performance | `perf(db): optimize user query` |
| `test` | Add or update tests | `test(auth): add login unit tests` |
| `build` | Build system or dependencies | `build: update dependencies` |
| `ci` | CI/CD configuration | `ci: add test workflow` |
| `chore` | Maintenance | `chore: update dev tools` |
| `revert` | Revert a commit | `revert: undo login endpoint changes` |
