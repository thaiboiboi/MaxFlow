
# Exercise: INCIDENT RESOLUTION (GQSC)

## Problem Description

Alpha Company produces fruit juice. Due to an unexpected incident, a batch of juice was damaged at the production warehouse and must be prevented from reaching the consumer warehouse.

The company has **N warehouses**, numbered from `1` to `N`:
- Warehouse `1` is the **production warehouse**
- Warehouse `N` is the **consumer warehouse**

The transportation system includes **M trucks**.  
Each truck transports goods **from one warehouse to another**.

Stopping a truck incurs a certain **cost**.

---

## Task

Determine the **minimum total cost** required to stop some trucks so that **no path exists**
from warehouse `1` to warehouse `N`.

---

## Input (`GQSC.INP`)

- First line: two integers `N`, `M`  
  (`2 ≤ N ≤ 50`, `0 ≤ M ≤ 1000`)
- Next `M` lines: three integers `A B C`  
  - A truck transports goods from warehouse `A` to warehouse `B`
  - Stopping this truck costs `C`

---

## Output (`GQSC.OUT`)

- One integer: the **minimum total cost**

---

## Notes

- The graph is **directed**
- This is a **Minimum Cut** problem
- Can be solved using **Max Flow / Min Cut**
