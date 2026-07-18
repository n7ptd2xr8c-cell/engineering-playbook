# Commit Convention

## Purpose

This document defines the commit message conventions used throughout my software engineering projects.

The objective is to produce a clean, meaningful, and understandable Git history.

Every commit should communicate **what changed** and represent **one logical unit of work**.

---

# General Principles

A good commit should be:

- small
- focused
- descriptive
- easy to understand

One commit should represent one logical change.

Avoid combining unrelated modifications.

---

# Commit Format

Use the following format whenever possible:

<type>: <short description>

Examples:

docs: define project organization standards

fix: handle crossword multiple solutions

feat: add search functionality

refactor: simplify validation logic

test: add crossword edge cases

---

# Common Types

## feat

A new feature.

Example:

feat: implement artist search

---

## fix

A bug fix.

Example:

fix: validate duplicate crossword words

---

## docs

Documentation only.

Example:

docs: define Git workflow standards

---

## refactor

Improve existing code without changing behavior.

Example:

refactor: simplify slot validation

---

## test

Add or improve tests.

Example:

test: add multiple solution cases

---

## chore

Maintenance tasks.

Example:

chore: update repository structure

---

# Writing Good Descriptions

Descriptions should:

- begin with a verb
- describe the result
- remain concise

Good:

fix: handle empty puzzle

Good:

docs: define debugging workflow

Avoid:

fix stuff

update

changes

final version

new commit

---

# Commit Frequency

Commit after:

- completing one logical task
- fixing one bug
- finishing one documentation section
- completing one feature

Avoid committing after every line of code.

Avoid waiting until the entire project is finished.

---

# Before Committing

Verify:

- the project builds
- tests pass when available
- debugging code has been removed
- only intended files are staged

Every commit should leave the project in a usable state whenever possible.

---

# Long-Term Goal

A developer should be able to understand the entire evolution of the project simply by reading the Git history.

Commit messages are documentation for future developers, including your future self.