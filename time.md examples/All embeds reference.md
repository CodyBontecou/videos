# All embeds reference

Every embed type the time.md plugin ships, with every parameter shown.
Useful as a copy-paste cheat sheet.

---

## stat — one big number

```timemd
view: stat
metric: total_time
title: Total time
```

```timemd
view: stat
metric: top_app
title: Top app
```

```timemd
view: stat
metric: apps_count
title: Apps tracked
```

```timemd
view: stat
metric: days
title: Days tracked
```

```timemd
view: stat
metric: peak_day
title: Peak day
```

---

## overview — stats + trend + heatmap + top apps

Full overview:

```timemd
view: overview
title: Overview
```

Lean overview — stats and apps only, last 7 days, top 3 apps:

```timemd
view: overview
sections: stats, apps
days: 7
limit: 3
title: Last week
```

Single-day overview (requires Raw Sessions in the export):

```timemd
view: overview
date: today
title: Today
```

```timemd
view: overview
date: yesterday
title: Yesterday
```

```timemd
view: overview
date: 2026-05-01
title: 2026-05-01
```

---

## trend-chart — daily line chart

```timemd
view: trend-chart
days: 14
title: Last 2 weeks
```

---

## heatmap — 7×24 weekly heatmap

```timemd
view: heatmap
title: Weekly pattern
```

---

## top-apps — app bar list

```timemd
view: top-apps
limit: 5
title: Top 5 apps
```

---

## categories — category bar list

```timemd
view: categories
limit: 5
title: Top 5 categories
```

---

## details — recent sessions list

```timemd
view: details
limit: 20
title: Last 20 sessions
```

---

## projects — categories with donut + stats

```timemd
view: projects
title: Projects
```

---

## distribution — donut + legend + stats

```timemd
view: distribution
title: Distribution
```

```timemd
view: distribution
stats: false
title: Donut + legend only
```

```timemd
view: distribution
stats: false
legend: false
label: false
title: Donut only — hover a slice
```

---

## web-history — timeline / domains / activity

```timemd
view: web-history
tab: timeline
limit: 50
title: Web timeline
```

```timemd
view: web-history
tab: domains
title: Top domains
```

```timemd
view: web-history
tab: activity
title: Activity by hour
```

```timemd
view: web-history
browser: Arc
tab: timeline
limit: 30
title: Arc browser only
```

---

## reports — bar charts + sortable table + export

```timemd
view: reports
groupBy: app
format: csv
title: Apps report
```

```timemd
view: reports
groupBy: category
format: json
title: Categories report
```

```timemd
view: reports
groupBy: day
format: markdown
title: Daily report
```
