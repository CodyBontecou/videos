# Reports

The **Reports** view bundles three pieces: time distribution per day,
weekday averages, and a sortable report table. Each Group by setting
re-shapes the table.

## By app

```timemd
view: reports
groupBy: app
title: Apps report
```

## By category

```timemd
view: reports
groupBy: category
title: Categories report
```

## By day

```timemd
view: reports
groupBy: day
title: Daily report
```

## Set the export format

`format` controls what the in-view **Export** button copies to the
clipboard. Accepts `csv`, `json`, or `markdown`.

```timemd
view: reports
groupBy: app
format: markdown
title: Apps report — markdown export
```
