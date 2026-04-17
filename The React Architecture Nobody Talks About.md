---
title: The React Architecture Nobody Talks About
tags: [react, architecture, patterns, typescript]
date: 2024-02-03
---

Everyone shows you folder structure. Nobody shows you the decision-making behind it. This video is about how large React apps actually fail — not from wrong folder names, but from leaked state, tangled data flow, and components that know too much.

## The actual problems

- State that should be local ends up global (and vice versa)
- Components reaching into sibling trees through context hacks
- Form state duplicated across three layers
- "Smart" components that are just disguised god objects

We'll refactor a real messy codebase live, applying domain boundaries, feature-scoped state, and a clean data contract between UI and business logic.
