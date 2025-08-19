---
aliases: []
date_created:
date_modified:
tags:
  - daily-note
title: Daily Review
---

# Daily Review

For {{date:YYYY-MM-DD}}.

## Highlights

What went well?

1. [x]

## Challenges

What was difficult?

1. [x]

## Thoughts

Gratitude and other reflections.

1. [x]

## Notes Created Today

```dataview
List FROM "" WHERE file.cday = date({{date:YYYY-MM-DD}}) SORT file.ctime asc
```

## Notes Modified Today

```dataview
List FROM "" WHERE file.mday = date({{date:YYYY-MM-DD}}) SORT file.mtime asc
```
