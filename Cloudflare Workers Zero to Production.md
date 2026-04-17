---
title: Cloudflare Workers — Zero to Production
tags: [cloudflare, workers, serverless, edge]
date: 2024-02-20
id: e37f8a2a-f30d-41a7-9409-a0de7ded28e8
---

Cloudflare Workers run at the edge, in 300+ locations, with cold starts under 1ms. This video covers the full mental model shift from "server" thinking to "edge function" thinking, then builds a real API with D1, KV, and R2.

## Agenda

- The Worker execution model (no Node.js, no libuv)
- When D1 (SQLite) beats Postgres for edge apps
- KV for sessions, R2 for files
- Wrangler workflows that don't drive you insane
- Costs: what's actually free and what bites you at scale

Live deploy at the end — real domain, real traffic, zero servers.