
# Exercise: TRADE FAIR (FAIR)

## Problem Description

There are **N companies** participating in a trade fair and **M exhibition locations**.

- Each company can be assigned to **only one location**
- Each location can host **only one company**
- Each company has a list of preferred locations

---

## Task

Determine the **maximum number of companies**
that can be assigned to a preferred location.

---

## Input (`FAIR.INP`)

- First line: `N M` (`1 ≤ N, M ≤ 200`)
- Next `N` lines:
  - First integer: number of preferred locations
  - Followed by the indices of preferred locations

---

## Output (`FAIR.OUT`)

- One integer: the **maximum number of companies** assigned

---

## Notes

- Bipartite matching problem
- Can be solved using **Max Flow**
