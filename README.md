# Competitive Programming

C++ solutions to problems from **LeetCode**, **Codeforces**, and **CodeChef**, plus a small set of reusable DSA templates. Built while training for contests, interviews, and core CS fundamentals — data structures, graph theory, greedy, DP, and bit manipulation come up often.

### Stats

- LeetCode rating: 1850+
- HackerRank: 5-star (C++)
- GATE CS: 99th percentile

### Structure

- **Root (`LeetCode_*.cpp`)** — LeetCode solutions, named by problem number (e.g. `LeetCode_2947.cpp` solves LeetCode #2947).
- **`codeforces/`** — Codeforces solutions, named by problem ID (e.g. `929_c.cpp` = Codeforces problem 929C).
- **`codechef/`** — CodeChef Starter-contest solutions, named by problem title.
- **`templates/`** — reusable building blocks pulled out for reuse across problems:
  - `disjoint_set.cpp` — Union-Find with union-by-size and path compression.
  - `next_greater.cpp` — next-greater-element via a monotonic stack.
  - `segment_tree_sum.cpp` — segment tree for range-sum queries with point updates.

This repo consolidates what used to be four separate repos (`LeetCode`, `codeforces`, `Contest`, `DSA`) into one, organized by platform.
