# Git Workflow

## Purpose

This document defines the Git workflow used throughout my software engineering projects.

The objective is to maintain a clean, understandable, and professional project history while supporting efficient collaboration with both humans and AI.

---

# General Philosophy

Git is not only a backup system.

Git is a tool for documenting the evolution of a software project.

Every commit should represent a meaningful step in the project's history.

---

# Standard Workflow

Whenever possible, follow this sequence:

1. Understand the task.
2. Plan the implementation.
3. Implement one logical change.
4. Test the solution.
5. Review the changes.
6. Commit.
7. Push.

Avoid committing unfinished or unrelated work.

---

# Branches

Prefer working on feature branches for significant changes.

Examples:

- feature/search
- feature/authentication
- fix/api-validation
- docs/playbook

Keep branch names short and descriptive.

---

# Commit Frequency

Commit frequently.

A commit should represent one logical change.

Avoid:

- extremely large commits
- commits containing unrelated work
- committing broken code unless explicitly required

Small commits make debugging and reviewing much easier.

---

# Before Every Commit

Before committing:

- review the modified files
- remove temporary debugging code
- ensure the project still works
- verify that only intended changes are included

Do not commit accidental modifications.

---

# Push Strategy

Push regularly after completing meaningful work.

Do not wait until an entire project is finished.

Frequent pushes provide:

- backup
- collaboration
- easier recovery
- cleaner history

---

# Working With AI

When collaborating with AI:

- discuss the implementation before modifying code
- keep changes focused
- preserve the existing architecture
- review generated code before committing

The developer remains responsible for every commit.

---

# Repository Management

Whenever possible:

- keep repositories independent
- maintain a clear README
- include a LICENSE when appropriate
- organize documentation consistently

Each repository should be understandable on its own.

---

# Continuous Improvement

Git history should tell the story of the project.

A developer should be able to understand how the project evolved simply by reading the commit history.