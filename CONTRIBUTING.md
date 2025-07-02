# Contributing to Commit Base

Thank you for your interest in contributing!  
To keep this repository clean and consistent, please follow the rules below for every Pull Request.

---

## Commit Message Guidelines

All commit messages **must follow this format**:

```sh
<type>(<scope>): <subject> :<emoji>:
```

**Allowed types:**  
`feat`, `fix`, `docs`, `refactor`, `chore`, `test`, `build`, `ci`, `revert`

**Scope:**  
The feature, module, or section affected (use lowercase, numbers, or hyphens).

**Subject:**  
Short summary of the change (start with a lowercase letter, no period at the end).

**Emoji:**  
A [GitHub emoji code](https://gist.github.com/rxaviers/7360908) describing the change, required at the end.

**Examples:**
- `feat(auth): add OAuth2 support :sparkles:`
- `fix(ui): resolve button alignment bug :bug:`
- `docs(readme): improve usage instructions :memo:`
- `revert(auth): restore legacy login method :rewind:`

---

## Pull Request Rules

- **Do not remove or rename the following files:**  
  - `README.md`
  - `LICENSE`
  - `.gitignore`
- **Every PR must pass all Commit Base Checks** (commit message lint, and required files must exist).
- If you break the format, CI will fail and your PR will not be merged until fixed.

---

## Submitting a Pull Request

1. **Fork** the repository and create your branch from `main`.
2. Ensure all commit messages follow the required format.
3. Check that `README.md`, `LICENSE`, and `.gitignore` exist in the root directory.
4. Submit your pull request and wait for automatic checks.
5. Fix any issues that fail CI (review error messages for details).
6. Be responsive to reviews and feedback.

---

## Need Help?

If you have questions about the commit format or workflow,  
please [open an issue](https://github.com/NeaByteLab/Commit-Base/issues) or contact the maintainers.

---

Thank you for keeping this repository high-quality and consistent!  
Happy contributing! 🚀