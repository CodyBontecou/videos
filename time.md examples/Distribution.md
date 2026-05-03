# Distribution

The right-hand column from the **Projects** view, available as a single
embed. The donut is interactive — hover a slice and the center swaps to
that category's name, total time, and percentage.

## Default

```timemd
view: distribution
title: Distribution
```

## Donut + legend, no STATS

```timemd
view: distribution
stats: false
title: Where the time goes
bare: true
```

## Donut only — hover a slice for the category info

```timemd
view: distribution
stats: false
legend: false
label: false
```

## Donut only, no embed chrome (matches note background)

```timemd
view: distribution
stats: false
legend: false
label: false
bare: true
```
