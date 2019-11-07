---
layout: post
title: DateRange in Kotlin
date: 2019-11-07
tags: [kotlin]
published: true
---

Kotlin has closed ranges which are useful for many things. When you want to check if two date ranges overlap you can use the beneath for an extension function `overlap` to calculate if two ranges overlap.

```kotlin
typealias DateRange = ClosedRange<LocalDate>

fun ClosedRange<LocalDate>.overlap(dateRange: ClosedRange<LocalDate>): Boolean =
        dateRange.start <= this.endInclusive && dateRange.endInclusive >= this.start
```

Now you can specifiy a date range via `val dateRange: DateRange = LocalDate.now()..LocalDate.now().plusDays(1)` for example. 
