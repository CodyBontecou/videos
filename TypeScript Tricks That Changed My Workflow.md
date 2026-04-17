---
title: TypeScript Tricks That Changed My Workflow
tags: [typescript, dx, productivity, types]
date: 2024-03-14
---

Not the basics. The patterns that actually change how you design code — discriminated unions for state machines, template literal types for API routes, and `infer` for extracting types you don't control.

## The hits

- `satisfies` vs `as const` vs direct annotation: when each wins
- Branded types to prevent `userId` where `postId` belongs
- Recursive conditional types for deep-partial (and when to stop)
- Type-safe event emitters in 25 lines
- `NoInfer<T>` to lock generic inference at the call site

All pulled from real code I've shipped. No toy examples.
