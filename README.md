# Git Commit Message Convention Guide

## ✅ Common Commit Types and Examples (with @ prefix)

| Type      | Purpose                                                | Example Commit Message                                          |
|-----------|--------------------------------------------------------|-----------------------------------------------------------------|
| @feat     | A new feature                                          | `@feat: add user login functionality`                          |
| @fix      | A bug fix                                              | `@fix: resolve null pointer in auth middleware`                |
| @style    | Code formatting, no logic changes                      | `@style: format code with Prettier`                            |
| @refactor | Code refactoring (no feature or bug fix)               | `@refactor: simplify user session handling logic`              |
| @perf     | Performance improvements                               | `@perf: optimize image loading on homepage`                    |
| @test     | Adding or updating tests                               | `@test: add unit tests for auth middleware`                    |
| @docs     | Documentation only changes                             | `@docs: update README with deployment instructions`            |
| @chore    | Misc tasks like tooling, maintenance                   | `@chore: update dependencies`                                  |
| @build    | Changes that affect the build system or dependencies   | `@build: update Webpack config for production`                 |
| @ci       | Changes to CI/CD config (e.g. GitHub Actions, Travis)  | `@ci: add lint step to GitHub Actions workflow`                |
| @revert   | Reverts a previous commit                              | `@revert: @feat(auth): add login functionality`                |

---

## 🔧 Sample Commit Messages

```bash
git commit -m "@feat: add user login functionality"
git commit -m "@fix: resolve null pointer in auth middleware"
git commit -m "@style: format code with Prettier"
git commit -m "@refactor: simplify user session handling logic"
git commit -m "@perf: optimize image loading on homepage"
git commit -m "@test: add unit tests for auth middleware"
git commit -m "@docs: update README with deployment instructions"
git commit -m "@chore: update dependencies"
git commit -m "@build: update Webpack config for production"
git commit -m "@ci: add lint step to GitHub Actions workflow"
git commit -m "@revert: @feat(auth): add login functionality"
