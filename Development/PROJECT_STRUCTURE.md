# Project Structure

## Purpose

This document defines how software projects should be organized.

The objective is to keep projects easy to understand, maintain, and extend while avoiding unnecessary complexity.

Project organization should remain consistent across different programming languages whenever possible.

---

# General Principles

A project structure should:

- separate responsibilities
- remain easy to navigate
- scale naturally as the project grows
- avoid unnecessary nesting
- prioritize clarity over clever organization

A new contributor should quickly understand where everything belongs.

---

# Keep the Root Clean

The project root should contain only important files.

Typical examples include:

- README
- LICENSE
- .gitignore
- project configuration
- entry point
- documentation

Avoid placing implementation files directly in the root unless the project is intentionally small.

---

# Organize by Responsibility

Files should be grouped according to what they do rather than when they were created.

Examples include:

- handlers
- services
- models
- utilities
- assets
- templates
- tests

Each directory should have a single responsibility.

---

# Documentation

Documentation should live alongside the project.

Whenever appropriate, include:

- README
- PRD
- Architecture
- AI project guide
- Audit notes

Documentation should remain synchronized with implementation.

---

# Naming

Use descriptive names.

Names should explain purpose rather than implementation.

Avoid abbreviations unless they are widely understood.

Consistency is more important than personal preference.

---

# Growth

Start simple.

Do not create folders for code that does not yet exist.

Allow the project structure to evolve naturally as new requirements appear.

Avoid premature organization.

---

# Consistency

Once a project structure has been established:

- preserve it
- extend it consistently
- avoid unnecessary restructuring

A consistent project is easier to maintain than a constantly changing one.

---

# Long-Term Objective

A project's structure should make the codebase predictable.

Developers should spend their time understanding the business logic rather than searching for files.