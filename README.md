# Minimum Spanning Tree Visualizer

DAA group project by 7 students. Visualizes Kruskal's and Prim's algorithms step by step on a graph you draw.

## Run it
Open `index.html` in a browser. No install needed. With GitHub Pages enabled it also runs online.

## Features
Add, move and delete nodes and edges, undo, sample graphs, random graph, build a graph from text, Kruskal and Prim step by step with Play, Pause, Next, Prev, speed and a step slider, Union-Find and priority queue display, sorted edge list, adjacency matrix, pseudocode with live highlighting, test suite, performance benchmark, dark and light mode, keyboard shortcuts.

## Team: 7 members, equal contribution


| # | Module | Owner file | What it does |
|---|---|---|---|
| 1 | Graph Editor | `ui.js`, `style.css` | Canvas, add/move/delete nodes and edges, undo |
| 2 | Graph Data | `graphdata.js` | Sample graphs, random graph, text import/export, adjacency matrix |
| 3 | Kruskal | `kruskal.js` | Sorting, Union-Find, step generation, sorted edge list |
| 4 | Prim | `prim.js` | Priority queue, start node, step generation |
| 5 | Playback | `animation.js` | Play, Pause, Next, Prev, speed, step slider, step log, shortcuts, dark mode |
| 6 | Testing | `tests.js` | Test suite, random graph checks, edge cases, benchmark |
| 7 | Documentation | `docs.js`, `README.md` | Pseudocode, complexity notes, comparison table, README |

Shared files (`index.html`, `state.js`, `main.js`) have no single owner. Change them only for your own module and tell the group.

## Complexity
Kruskal: O(E log E). Prim: O(V·E) in this simple version, O(E log V) with a heap.
