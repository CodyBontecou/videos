---
title: Why I Switched from Webpack to Bun
tags: [bun, bundler, performance, devtools]
date: 2024-03-01
id: 6dc57c5e-ae6b-466a-b36d-64c7e09da330
---

After six years of Webpack configs, I migrated a 200k-line TypeScript monorepo to Bun in a week. Here's what was better, what was worse, and the one thing that almost made me revert.

## The honest breakdown

**Better:** Cold build time went from 42s to 4s. Hot reload is instant. The config is 8 lines.

**Worse:** Some Webpack plugins have no equivalent. Source maps are occasionally wrong. The ecosystem is younger — you feel it.

**The near-revert:** Tree-shaking behavior differs from Rollup in edge cases that matter if you're shipping a library.

Would I do it again? Yes. Would I recommend it blindly? Depends on your dependency graph.