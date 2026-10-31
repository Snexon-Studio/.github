# Contributing to Snexon

Thank you for your interest in contributing to Snexon open-source systems.

## Engineering Principles

1. **Anti-Slop Standard**: All technical documentation, code comments, and commit messages must describe concrete mechanics. Avoid marketing adjectives and unsubstantiated performance claims.
2. **Determinism**: Code must compile and run predictably across target environments without relying on undocumented side effects.
3. **Safety & Validation**: Input boundaries must enforce strict validation. Public APIs must handle edge conditions explicitly without silent error suppression.

---

## Development Workflow

1. **Fork & Branch**: Fork the target repository and create a branch named `fix/<issue-number>-<slug>` or `feat/<slug>`.
2. **Coding Style**:
   - Adhere to the established repository linter and formatter settings.
   - For UI projects, conform strictly to the **Snexon Design System** (Deep Obsidian `#07070C`, squircle geometries, specular borders).
3. **Tests**: Add unit or integration tests that verify new functionality or prevent regressions of fixed defects.
4. **Pull Requests**:
   - Provide a factual summary of changes.
   - Reference open issue numbers.
   - Verify that CI passes before requesting review.
