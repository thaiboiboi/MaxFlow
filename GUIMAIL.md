
# Exercise: SEND MAIL (GUIMAIL)

## Problem Description

Binh's company has **N computers** (`1` to `N`) connected by network cables.

- If two computers are directly connected, they can send mail to each other
- Mail can also be sent through **intermediate computers**
- Some computers may be **broken**

---

## Task

Given two computers `a` and `b`, determine the **minimum number of computers**
that must be broken so that mail **cannot** be sent between them.

Computer `a` and `b` are **not directly connected**.

---

## Input (`GUIMAIL.INP`)

- First line: four integers `N M a b`  
  (`1 ≤ N ≤ 100`, `1 ≤ M ≤ 1000`)
- Next `M` lines: two integers `X Y`  
  - A cable connects computer `X` and computer `Y`

---

## Output (`GUIMAIL.OUT`)

- One integer: the **minimum number of computers** that must be broken

---

## Notes

- Undirected graph
- This is a **minimum vertex cut** problem
- Can be solved using **Max Flow** with node splitting
