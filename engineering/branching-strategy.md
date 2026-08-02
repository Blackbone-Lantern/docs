# Branching Strategy

This document defines the branching strategy used across all Blackbone Software projects.

The goal is to keep the project history clean, understandable and easy to maintain.

---

## Main Branch

The `main` branch always represents the current stable state of the project.

Direct development on `main` should be avoided.

All changes are implemented in dedicated branches and merged through a Pull Request.

---

## Branch Types

### `feature/`

Used for implementing new functionality.

**Example**

```text
feature/image-resize
feature/ai-upscaling
feature/social-media-presets
```

---

### `fix/`

Used for bug fixes.

**Example**

```text
fix/png-export
fix/android-file-picker
```

---

### `refactor/`

Used for internal improvements without changing application behaviour.

**Example**

```text
refactor/image-processing-service
refactor/export-pipeline
```

---

### `docs/`

Used for documentation changes only.

**Example**

```text
docs/engineering-playbook
docs/setup-guide
```

---

### `test/`

Used for adding or improving automated tests.

**Example**

```text
test/image-resizer
test/export-service
```

---

### `chore/`

Used for maintenance, tooling, infrastructure and project configuration.

**Example**

```text
chore/project-foundation
chore/eslint
chore/github-actions
```

---

## General Rules

- Create branches from the latest `main`.
- Each branch should solve one coherent problem.
- Keep branches short-lived.
- Merge changes through a Pull Request.
- Delete branches after merging.

---

## Why We Work This Way

This strategy helps us to:

- keep the project history readable
- isolate changes
- simplify code reviews
- reduce merge conflicts
- ensure that `main` always stays stable

Branch names should clearly communicate the purpose of the work being done.

---

> **Engineering Principle**
>
> Branches describe *why* we are changing the project, not only *where* we are working.
