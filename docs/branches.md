# 🌿 Branching Strategy – cargo-ui-platform

This document outlines the branching model used in the `cargo-ui-platform` repository. It helps maintain a clean workflow between design, development, and production.

---

## 🔀 Branch Overview

| Branch Name       | Purpose                                                                 |
|-------------------|-------------------------------------------------------------------------|
| `main`            | Stable production-ready code. Only updated via approved Pull Requests. |
| `dev`             | Active development branch. All features and fixes are merged here first.|
| `bugfix/*`        | Fixes for UI or jQuery issues. Example: `bugfix/modal-close-issue`      |
| `docs/*`          | Documentation updates. Example: `docs/style-guide-update`               |
| `hotfix/*`        | Urgent fixes for production. Merged into both `main` and `dev`.         |

---

## 🧭 Workflow Guidelines

- Start new work from `dev`
- Use descriptive branch names
- Submit changes via Pull Request
- All merges to `main` require review and approval
- Protect `main` and optionally `dev` in GitHub settings

---

## 🛡️ Branch Protection Tips

- Enable **Require Pull Request before merging** on `main`
- Optionally enable **Require approvals** and **Status checks**
- Restrict direct pushes to `main` to maintain stability

---

## 📣 Notes

This branching model supports collaboration between designers and developers. It ensures that UI changes, design assets, and documentation updates are organized and traceable.

For questions or suggestions, feel free to open an issue or contact the maintainer.

