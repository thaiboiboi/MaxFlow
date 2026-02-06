
# Exercise: OIL TRANSPORTATION (DAU)

## Problem Description

Alpha City has an oil transportation system with:

- **N locations**
- **M directed pipelines**, each with a maximum daily capacity

Locations are divided into:
- **Oil wells** (sources)
- **Consumption stations** (sinks)
- **Intermediate stations** (flow in = flow out)

---

## Task

Determine the **maximum total amount of oil**
received at all consumption stations in one day.

---

## Input (`DAU.INP`)

- First line: `N M` (`2 ≤ N ≤ 100`, `2 ≤ M ≤ 500`)
- Next `M` lines: `A B C`  
  - Pipeline from `A` to `B` with capacity `C`

---

## Output (`DAU.OUT`)

- One integer: the **maximum total oil flow**

---

## Notes

- Multiple sources and sinks
- Solve using **Max Flow** with super source and super sink
