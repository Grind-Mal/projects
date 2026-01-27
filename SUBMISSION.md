# Broken Project Submission Rules

This document defines what is allowed into GrindMal.

If your project does not meet **all** requirements, it will be rejected without discussion.

---

## Mandatory Requirements

Your project MUST:

- Be runnable locally
- Use a public GitHub repository
- Contain exactly **one primary bug**
- Fail in a reproducible way
- Describe expected vs actual behavior
- Be solvable without external help
- Not require paid APIs, tokens, or secrets

---

## Bug Scope (Important)

Allowed:

- logic errors
- incorrect conditionals
- edge-case failures
- missing validation
- wrong return values
- incorrect calculations

Not allowed:

- architectural redesigns
- performance tuning
- feature additions
- “clean this up”
- vague or subjective issues

One repo = one problem.

---

## Difficulty Guidelines

**easy**

- beginner-friendly
- single-file or small scope
- fixable in < 30 minutes

**medium**

- multi-file
- requires tracing logic

**hard**

- deeper system understanding
- still bug-fixable, not redesign

If you mislabel difficulty, it will be corrected or rejected.

---

## Required Files in Your Repo

Your broken project repository MUST include:

- `README.md`
- `BUG.md`

`BUG.md` must clearly explain:

- how to reproduce the bug
- expected behavior
- actual behavior

Do NOT include the solution or hints.

---

## Enforcement

- Incomplete submissions are closed
- Arguments are ignored
- Complaints are ignor
