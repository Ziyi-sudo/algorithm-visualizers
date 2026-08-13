# Algorithm Visualizers

Interactive, step-by-step visualizers for classic algorithm patterns. Each one is a
single self-contained HTML page: press step, watch the pointers and state change, see
why the algorithm does what it does instead of reading that it works.

**▶ [Open the visualizers](https://ziyi-sudo.github.io/algorithm-visualizers/)**

## Why

Reading an algorithm's code tells you what it does. Watching the state change tells you
why it's correct. These were built while working through problems — every time an
invariant wasn't obvious from the code, it became a page here.

## Covered so far

- **Two pointers / sliding window** — window expansion and contraction, and what keeps the window valid
- **Hashing and deduplication** — how state accumulates across a pass
- **Graph traversal** — BFS ordering, deep copy with visited tracking, bipartite checking
- **Streaming** — first non-repeating character over a live stream
- **Voting** — Boyer-Moore majority, and why the counter can't go wrong



## Stack

Vanilla HTML, CSS, and JavaScript. No framework, no build step — each page opens on its
own. Deployed with GitHub Pages.

## Running locally

```bash
open 3sum-visualizer.html
```

Any page works standalone. No install needed.
