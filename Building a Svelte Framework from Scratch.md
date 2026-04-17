---
title: Building a Svelte Framework from Scratch
tags: [svelte, framework, javascript, compiler]
date: 2024-01-12
id: 64473bbb-0806-4f22-90b7-81c6aaa9a403
---

What if we stripped Svelte down to first principles and rebuilt it ourselves? This video walks through designing a minimal reactive compiler that transforms declarative component syntax into raw DOM operations — no virtual DOM, no diffing, just surgical updates.

## What we'll cover

- How Svelte's compiler turns `{count}` into `element.textContent = count`
- Writing a tiny reactive store from 40 lines of JavaScript
- Why compile-time reactivity beats runtime reactivity for most UIs
- Where the abstraction breaks and what Svelte does to handle it

The end goal: a working counter component built on our own framework, compiled and running in the browser with zero runtime overhead.