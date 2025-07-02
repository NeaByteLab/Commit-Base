# Commit Base

[![Install this app](https://img.shields.io/badge/GitHub%20App-Commit%20Base%20Linter-blue?logo=github)](https://github.com/apps/commit-base-linter)
![CI](https://github.com/NeaByteLab/Commit-Base/actions/workflows/standard-repo.yml/badge.svg)
![License](https://img.shields.io/github/license/NeaByteLab/Commit-Base)
![Last Commit](https://img.shields.io/github/last-commit/NeaByteLab/Commit-Base)
![Open Issues](https://img.shields.io/github/issues/NeaByteLab/Commit-Base)

**Commit Base** is an automated GitHub workflow that enforces commit message standards and repository quality checks for every **Pull Request** *and* **push to the main branch**.

---

## ✨ Features

* **Strict commit message linting** for every PR and push to main
* **README.md, LICENSE, and .gitignore** files are required in every branch
* **Clear error messages** for fast troubleshooting
* **Easy integration** with any GitHub repository
* **Fail-fast CI/CD**: no changes will be merged or pushed to main unless all checks pass

---

## 🚀 Quick Start

1. Copy `.github/workflows/standard-repo.yml` into your repository.
2. Ensure your project root contains `README.md`, `LICENSE`, and `.gitignore`.
3. Create a Pull Request **or** push to the main branch — Commit Base will automatically check everything!

---

## 📝 Commit Message Format

Every commit must follow this pattern:

```
<type>(<scope>): <subject> :<emoji>:
```

**Allowed types:** feat, fix, docs, refactor, chore, test, build, ci, revert

**Examples:**

* `feat(api): add payment endpoint :sparkles:`
* `fix(auth): fix token refresh bug :bug:`
* `docs(readme): update documentation :memo:`
* `revert(login): restore previous login logic :rewind:`

❗ If any commit message does not match this format, or if required files are missing, the check will fail and your PR or push will be blocked.

---

## ✅ Quality Gate Checks

* Enforces commit message format for all PRs and pushes to main
* Fails if `README.md`, `LICENSE`, or `.gitignore` is missing
* Clear error messages for fast troubleshooting

---


## 💡 Advanced Usage

* You can customize the workflow file to enforce more files or rules if needed.
* Add or edit allowed commit types and scopes by adjusting the workflow regex.
* The workflow can be extended for other branches (e.g., `dev`) by editing the trigger in the workflow YAML.

---

## 🙌 Contributing

Want to contribute? Please check out [CONTRIBUTING.md](CONTRIBUTING.md) for commit message format and PR rules.

---

## 🆘 Need Help?

- Found a bug or want a feature? [Open an issue](https://github.com/NeaByteLab/Commit-Base/issues)

---

## 📄 License

MIT © [NeaByteLab](https://github.com/NeaByteLab)