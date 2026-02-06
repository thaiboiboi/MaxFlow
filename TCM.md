
# Exercise: GREETING CARDS (TCM)

## Problem Description

During Christmas, An wants to send greeting cards to friends.

- An has **N cards** and **M envelopes**
- Each card has size `D × R`
- Each envelope has size `H × W`
- Each envelope can contain **at most one card**
- A card can be rotated

A card fits in an envelope if:
- `D ≤ H` and `R ≤ W`, or
- `D ≤ W` and `R ≤ H`

---

## Task

Determine the **maximum number of cards** An can send.

---

## Input (`TCM.INP`)

- First line: `N M` (`1 ≤ N, M ≤ 500`)
- Next `N` lines: `D R` — card dimensions
- Next `M` lines: `H W` — envelope dimensions

---

## Output (`TCM.OUT`)

- One integer: the **maximum number of greeting cards**

---

## Notes

- Bipartite matching problem
- Can be solved using **Max Flow**
