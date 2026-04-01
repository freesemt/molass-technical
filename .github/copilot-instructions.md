<!-- AI Context Standard v0.8.9 - Adopted: 2026-04-02 -->
# AI Assistant Initialization Guide — molass-technical

**Purpose**: Initialize AI context for working in this repository  
**Created**: March 25, 2026

---

## What this repository is about

This repository holds the Jupyter Book source for the [Molass Technical Report](https://biosaxs-dev.github.io/molass-technical/) web book — a technical report covering the algorithms and implementation details of the molass library.

---

## Repository-specific conventions

- **Format**: [MyST Markdown syntax](https://jupyterbook.org/en/stable/reference/cheatsheet.html) is used throughout unless otherwise stated
- **Build tool**: Jupyter Book
- **Audience**: Developers and researchers who need detailed technical documentation of the molass algorithms

---

## Multi-root workspace context

| Repository | Role | Tool |
|------------|------|------|
| `molass-library` | Main library (Python source) | Python / Sphinx |
| `molass-legacy` | Legacy GUI predecessor; required runtime dep | Python / Sphinx |
| `modeling-vs-model_free` | Research: decomposition criteria | Markdown / Notebooks |
| `molass-tutorial` | Usage documentation | Jupyter Book / MyST |
| `molass-essence` | Theory documentation | Jupyter Book / MyST |
| `molass-technical` | **This repo**: technical report | Jupyter Book / MyST |
| `molass-develop` | Developer handbook | Jupyter Book / MyST |
| `molass-beginner` | Beginner onboarding (Agent mode) | Markdown |

---

## Building the book

```bash
jupyter-book build .
```

Output goes to `_build/html/`.

---

## 🔄 Updates

**Latest**: March 25, 2026 — Created `.github/copilot-instructions.md` (AI Context Standard v0.8)
