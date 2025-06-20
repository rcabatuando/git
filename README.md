# Git Commit Message Convention Guide

## ✅ Common Commit Types and Examples (with @ prefix)

| Type      | Purpose                                                | Example Commit Message                                          |
|-----------|--------------------------------------------------------|-----------------------------------------------------------------|
| @init     | Initial project setup or scaffolding	                 | `@init: scaffold Vue 3 project with Vite + Tailwind + TS`      |
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

## 📝 Sample Git Commit Messages Using @Prefix Convention

```bash
# 🚀 New feature added
git commit -m "@feat: add user login functionality"
git commit -m "@feat: implement pagination on reports table"
git commit -m "@feat: added static page for LFP Narrative Report"

# 🐛 Bug fix
git commit -m "@fix: resolve null pointer in auth middleware"
git commit -m "@fix: correct table header alignment on mobile view"
git commit -m "@fix: Typo in 'Monitoring' label on dashboard"

# 🎨 Code formatting only (no logic change)
git commit -m "@style: format code with Prettier"
git commit -m "@style: fix spacing and indentation in form.vue"
git commit -m "@style: update table text color to base-darkblue"

# 🔨 Refactor code without changing behavior
git commit -m "@refactor: simplify user session handling logic"
git commit -m "@refactor: extract form validation into helper function"
git commit -m "@refactor: modularize report components"

# ⚡ Improve performance
git commit -m "@perf: optimize image loading on homepage"
git commit -m "@perf: reduce chart rendering lag on reports page"

# ✅ Add or improve tests
git commit -m "@test: add unit tests for auth middleware"
git commit -m "@test: create test suite for table filtering logic"

# 📚 Documentation only
git commit -m "@docs: update README with deployment instructions"
git commit -m "@docs: add API contract for Monitoring Reports"

# 🧹 General maintenance (non-prod logic)
git commit -m "@chore: update dependencies"
git commit -m "@chore: clean up unused assets"
git commit -m "@chore: remove console logs across project"

# 🏗️ Build-related changes (webpack, vite, etc.)
git commit -m "@build: update Webpack config for production"
git commit -m "@build: add postcss plugin for Tailwind CSS"

# 🤖 CI/CD related changes
git commit -m "@ci: add lint step to GitHub Actions workflow"
git commit -m "@ci: fix broken test step in CI pipeline"

# ⏪ Revert previous commit
git commit -m "@revert: @feat(auth): add login functionality"
git commit -m "@revert: @style: apply incorrect color scheme"
