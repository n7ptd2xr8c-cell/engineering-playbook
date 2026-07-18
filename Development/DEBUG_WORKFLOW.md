# Debug Workflow

## Purpose

This document defines the debugging workflow used throughout my software engineering projects.

The objective is to solve problems systematically instead of relying on trial and error.

Debugging is considered part of software engineering rather than a separate activity.

---

# General Principle

Never guess.

Every debugging step should be based on evidence.

Before changing code, understand why the current behavior is incorrect.

---

# Standard Workflow

## Step 1 — Read the Error

Read the complete error message.

Do not immediately search for a solution.

Understand:

- what failed
- where it failed
- when it failed

The error message usually contains valuable information.

---

## Step 2 — Reproduce the Problem

Verify that the issue can be reproduced consistently.

If the bug cannot be reproduced, avoid making changes until the behavior is better understood.

---

## Step 3 — Verify Assumptions

Question every assumption.

Examples:

- Is this function actually being called?
- Is the variable what I expect?
- Is the API returning what I think?
- Is the input valid?
- Is this code even executing?

Never debug assumptions.

Debug facts.

---

## Step 4 — Isolate the Problem

Reduce the scope.

Identify the smallest piece of code responsible for the incorrect behavior.

Avoid changing multiple areas simultaneously.

---

## Step 5 — Identify the Root Cause

Fix the cause.

Do not only fix the visible symptom.

Temporary workarounds should only be used when absolutely necessary.

---

## Step 6 — Apply the Smallest Fix

Prefer small changes.

Large modifications make debugging more difficult.

One logical change is easier to verify than many unrelated changes.

---

## Step 7 — Verify the Fix

After implementing the solution:

- rerun tests
- verify expected behavior
- verify related functionality
- ensure nothing else broke

A fix is complete only after verification.

---

# Debugging Techniques

Useful techniques include:

- reading stack traces
- using console output
- printing intermediate values
- simplifying inputs
- checking boundary cases
- comparing expected vs actual behavior

Choose the simplest technique that provides useful information.

---

# Working with AI

When debugging with AI:

Provide:

- the error
- the relevant code
- expected behavior
- actual behavior
- attempted solutions

The more precise the information, the better the debugging process.

---

# Common Mistakes

Avoid:

- random code changes
- copying solutions without understanding
- changing multiple files unnecessarily
- ignoring warning messages
- assuming the first hypothesis is correct

---

# Long-Term Goal

A good developer spends less time guessing and more time investigating.

The objective is to become systematic, confident, and efficient when solving software problems.