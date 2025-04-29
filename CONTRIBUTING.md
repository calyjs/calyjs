# Contributing Guidelines

Thank you for your interest in contributing to this project! To maintain consistency and quality, we kindly ask all contributors to follow these guidelines.

---

## 📁 Branching Strategy

All new work must begin from a new branch created off the latest `develop` branch.

### ✅ Accepted Branch Name Formats:
- `feature/<short-description>` — New feature implementation
- `fix/<short-description>` — Bug fixes
- `chore/<short-description>` — Maintenance tasks
- `docs/<short-description>` — Documentation updates
- `style/<short-description>` — Code style or formatting changes
- `refactor/<short-description>` — Code restructuring
- `ci/<short-description>` — CI/CD pipeline or config updates
- `ticket/<ticket-id>` — Work related to specific tickets
- `revert/<commit-hash>` — Reverts to a previous state

---

## 📦 Development Workflow

1. **Fork the repository** (if you don't have write access).
2. **Create your branch** using an appropriate prefix as described above.
3. Make your changes and ensure:
   - Code follows project standards and style.
   - All tests pass (run `npm test`, `yarn test`, or equivalent).
   - You have added/updated documentation as needed.
4. **Commit your changes** with meaningful commit messages.
5. **Push your branch** and open a **Pull Request (PR)** targeting the `develop` branch.

---

## 🔁 Pull Request Lifecycle

- PR must target `develop` branch.
- All status checks (CI, tests, linters) must pass.
- Reviews and approvals are required before merging.

Once your changes are merged into `develop`, a new PR must be created for the `master` branch.

---

## 🚀 Release Process

After a PR is approved and merged into `master`, the release process is triggered **manually** by maintainers.

---

## 💬 Questions or Suggestions?

Please open a [Discussion](https://github.com/calyjs/calyjs/discussions) or create an [Issue](https://github.com/calyjs/calyjs/issues) if you have questions, suggestions, or feedback.

---

Thank you for helping us improve this project! 🚀
