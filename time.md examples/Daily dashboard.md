# Daily dashboard

A drop-in template for a daily note. Embeds the core stat cards, today's
trend sparkline, the weekly heatmap, and the top 5 apps for today.

## Today at a glance

```timemd
view: stat
metric: total_time
title: Screen time today
```

```timemd
view: overview
date: today
sections: stats, apps
limit: 5
title: Today
```

## This week

```timemd
view: trend-chart
days: 7
title: Last 7 days
```

```timemd
view: heatmap
title: Weekly pattern
```

## Top apps (all time)

```timemd
view: top-apps
limit: 10
```
