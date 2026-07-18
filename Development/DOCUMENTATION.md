# Documentation Standards

## Purpose

This document defines the documentation standards used throughout my software engineering projects.

The objective is to create documentation that improves understanding, communication, maintenance, and collaboration without becoming unnecessary overhead.

Documentation should explain the project, not duplicate the code.

---

# Documentation Philosophy

Documentation exists to answer questions.

Each document should have a clear purpose.

If a document no longer provides value, it should be updated or removed.

Avoid writing documentation simply because it is expected.

---

# Documentation Pyramid

Projects should document information at different levels.

README

↓

PRD (Project Requirements)

↓

Architecture

↓

Implementation

↓

Audit Notes

Each level answers different questions.

---

# README

Purpose:

Explain the project at a high level.

Typical contents:

- project overview
- features
- installation
- usage
- technologies
- project structure

A new developer should understand the project after reading the README.

---

# PRD (Project Requirements Document)

Purpose:

Describe what the project should accomplish.

Typical contents:

- objectives
- requirements
- constraints
- success criteria
- scope

The PRD explains the problem before discussing the solution.

---

# Architecture Document

Purpose:

Explain how the system is organized.

Typical contents:

- system components
- responsibilities
- data flow
- design decisions
- trade-offs

Architecture explains why the implementation looks the way it does.

---

# Implementation

The code explains the implementation.

Documentation should not duplicate the source code.

Use comments only when they explain intent or important decisions.

---

# Audit Notes

Purpose:

Record important implementation decisions, lessons learned, debugging discoveries, and audit preparation.

Examples:

- common questions
- difficult bugs
- architecture explanations
- important design decisions
- project-specific knowledge

Audit notes help preserve experience for future reviews.

---

# AI Documentation

When using AI during development:

Document:

- implementation plans
- design decisions
- important trade-offs

Avoid documenting every conversation.

Keep only information that provides long-term value.

---

# Documentation Maintenance

Documentation should evolve together with the project.

Whenever the implementation changes significantly:

- review affected documentation
- update outdated information
- remove obsolete sections

Outdated documentation is worse than missing documentation.

---

# Writing Style

Documentation should be:

- concise
- structured
- technically accurate
- easy to navigate

Prefer simple language over unnecessary complexity.

---

# Long-Term Goal

Good documentation reduces onboarding time, simplifies maintenance, and preserves engineering knowledge.

Every document should help future developers—including my future self—understand the project more quickly.