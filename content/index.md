---
title: Welcome
description: My engineering learning journal
date: 2026-06-25
---

# Learning in Public

Welcome to my notes. Here I document what I'm learning in engineering,
math, and computer science.

## Math works out of the box

Inline: $E = mc^2$

Block:
$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$

## So does code

```python
def binary_search(arr, target):
    lo, hi = 0, len(arr) - 1
    while lo <= hi:
        mid = (lo + hi) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            lo = mid + 1
        else:
            hi = mid - 1
    return -1
```