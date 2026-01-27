# GrindMal — Broken Projects Registry

This repository is the **index** of all broken projects used in GrindMal cycles.

This repo does **not** contain code.
It contains:

- rules
- submissions
- references

All actual broken projects live in **separate repositories** under the `grindmal/` organization.

---

## What is a “Broken Project”?

A broken project is a **real, runnable project** with:

- a **specific, intentional bug**
- a **clear expected behavior**
- a **verifiable failure**

It is NOT:

- a tutorial
- a refactor exercise
- a feature request
- an architecture redesign

You fix things by submitting **code**, not explanations.

---

## How GrindMal Works (Loop)

1. A broken project is submitted via Issue
2. The project repo is reviewed for validity
3. Contributors fork the broken repo
4. Fixes are submitted as PRs
5. PRs are reviewed using GrindMal rules
6. Accepted fixes are merged
7. The project is marked as solved

Learning happens by:

- reading diffs
- reviewing PRs
- seeing real mistakes corrected

---

## Rules (Read Carefully)

- Help = Pull Request
- Opinions without code are ignored
- Disputes are resolved via alternative PRs, not comments
- No private help channels
- No mentors
- No hand-holding

The system teaches. People adapt or leave.

---

## Repository Structure

- `SUBMISSION.md` → project submission rules
- `projects.json` → canonical list of accepted projects
- `.github/ISSUE_TEMPLATE` → enforced submission format

If you want to contribute, start with **SUBMISSION.md**.
