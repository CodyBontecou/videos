---
title: SQLite in Production — What They Don't Tell You
tags: [sqlite, database, backend, performance]
date: 2024-03-28
---

SQLite is not a toy database. It handles millions of reads per second, has ACID transactions, and ships in a single file. But there are real traps when you move from "localhost hobby project" to "this needs to not go down."

## The gotchas

- WAL mode: why you want it and what it costs
- Write contention under concurrent load (and the actual numbers)
- Backup strategies that don't require stopping the world
- Connection pooling is different — here's why
- The D1/Turso/Litestream tradeoffs for the edge

Final take: SQLite is underrated for apps under ~50k concurrent writes/day. Above that, the constraints become constraints.
