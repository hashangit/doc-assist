---
name: user-centric-development
description: >
  Meticulous, holistic implementation that centers the user's mental model.
  Use when implementing features, fixing bugs, refactoring, or modifying any code.
  Triggers on: "implement", "build", "fix", "refactor", "add feature", or any
  task that involves writing or modifying code.
---

# User-Centric Development

Before writing any code, internalize these three principles. Apply them to every implementation decision.

## 1. Meticulous Implementation

- Read every file you'll touch before editing. Never edit blindly.
- Trace the full execution path — from entry point to side effect — before changing logic.
- Verify types, contracts, and invariants at boundaries. Don't assume; confirm.
- When modifying existing code, preserve all existing behavior unless explicitly told to change it.
- Test edge cases mentally before writing: nulls, empties, concurrent access, error paths.

## 2. Holistic Awareness

- Map all files, functions, and data flows connected to the change before touching code.
- Identify downstream consumers — what else reads this data, calls this function, or renders this component?
- Check for shared patterns (hooks, utilities, types) that the change must stay consistent with.
- Consider the blast radius: a change in one file may require updates in tests, IPC handlers, database schemas, or UI components.
- Look for implicit contracts — unwritten assumptions between modules — and honor them.

## 3. User's Mental Model First

- Before implementing, articulate what the user expects to happen. This is the spec.
- If the implementation would produce behavior that contradicts the user's mental model, stop and clarify.
- Consider the user's workflow end-to-end, not just the code unit being changed.
- Error states, loading states, and empty states are part of the experience — handle them with the same care as the happy path.
- If a technical decision makes the UX worse, flag it before proceeding.

## Quick Checklist

Before writing code:
1. Do I understand the full connected graph of files and logic affected?
2. Can I describe what the user expects to see/experience after this change?
3. Am I preserving all existing behavior that isn't explicitly being changed?

If any answer is "no", investigate further before proceeding.
