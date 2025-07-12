---
aliases: 
date_created: 2021-08-30 00:08
date_modified: 2025-07-12 19:07
tags:
  - daily-note
title: Daily Review
---

# Daily Review

For {{date:YYYY-MM-DD}}.

## Today

### Highlights

What went well?

1. [x]

### Challenges

What was difficult?

1. [x]

## Tomorrow

### Priorities

Top priorities, in order of importance. Max 3.

1. [Complete or make progress on X by doing Y.]

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
