# Commit Base

![Commit Base Checks](https://github.com/NeaByteLab/Commit-Base/actions/workflows/standard-repo.yml/badge.svg)
![License](https://img.shields.io/github/license/NeaByteLab/Commit-Base)
![Last Commit](https://img.shields.io/github/last-commit/NeaByteLab/Commit-Base)
![Open Issues](https://img.shields.io/github/issues/NeaByteLab/Commit-Base)

**Commit Base** is an automated GitHub workflow that enforces commit message standards and repository quality checks for every Pull Request.

---

## ✨ Features

* **Strict commit message linting** for every PR
* **README.md, LICENSE, and .gitignore** files are required in every branch
* Easy integration with any GitHub repository
* Fail-fast CI/CD: PRs cannot be merged unless all checks pass

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

❗ If any commit message does not match this format, or if required files are missing, the Pull Request will fail and cannot be merged.

---

## ✅ Quality Gate Checks

* Enforces commit message format for all PRs
* Fails PR if `README.md`, `LICENSE`, or `.gitignore` is missing
* Clear error messages for fast troubleshooting

---

## 🚀 Quick Start

1. Copy `.github/workflows/standard-repo.yml` into your repository.
2. Make sure you have `README.md`, `LICENSE`, and `.gitignore` in your project root.
3. Create a Pull Request and see Commit Base in action!

---

## 🙌 Contributing

Want to contribute? Please check out [CONTRIBUTING.md](CONTRIBUTING.md) for commit message format and PR rules.

---

## 📄 License

MIT © [NeaByteLab](https://github.com/NeaByteLab)