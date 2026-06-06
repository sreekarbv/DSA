# DSA (Golang)

A compact, opinionated workspace for solving Data Structures & Algorithms problems in Go, organized around the Propeers roadmap: https://www.propeers.in/roadmaps/69692150442404dc257236a1

## What this repo is for

- Practice and record DSA solutions in Go (Golang).
- Keep implementations small and easy to read.
- Map learning progress to a focused roadmap so you can follow a study plan.

## Repository layout and conventions

- Organize problems by topic (folder per topic). Example folders:
  - `arrays/`, `strings/`, `linkedlists/`, `stack_queue/`, `trees/`, `graphs/`, `heaps/`, `hashing/`, `dp/`, `bitwise/`, `math/`, `greedy/`.

- Each problem: a single Go source file containing the solution and any lightweight helpers.
  - Naming: `001_two_sum.go` (use a zero-padded numeric prefix for ordering, then a descriptive name).
- Keep functions unexported unless they need to be used by other packages. Prefer small helper functions.
- Add a short comment at the top of each file describing the problem (source + constraints + complexity).

## Coding style / expectations

- Prefer clarity over cleverness. Aim for O(n) or better when possible and document complexity.
- Include a brief explanation of the approach in a comment or adjacent markdown when non-obvious.

## Roadmap mapping (based on the Propeers roadmap)

Follow these topic areas in order. Each bullet is a suggested folder/section and core focus.

- Fundamentals: Go basics, arrays, strings, pointers, slices.
- Arrays & Strings: Two pointers, sliding window, sorting-based, prefix/suffix sums.
- Linked Lists: Reversal, fast/slow pointers, merging, cycle detection.
- Stacks & Queues: Monotonic stacks, BFS/queue patterns, parentheses matching.
- Trees: Traversals, recursion, BST operations, tree DP, LCA.
- Heaps & Priority Queues: Kth element, merging streams.
- Hashing & Sets: Frequency counting, sliding-window with hashmaps.
- Graphs: BFS/DFS, shortest paths (Dijkstra), topological sort, union-find.
- Greedy: Interval scheduling, activity selection, greedy-choice proofs.
- Dynamic Programming: Subproblem identification, memoization, bottom-up DP, knapsack, LIS.
- Bit Manipulation & Math: Bit tricks, modular arithmetic, primality.

Each folder should contain progressively harder problems: easy -> medium -> hard.

## Study plan (lean)

- Daily: 1–2 problems (30–90 mins). Start with warmup from arrays/strings.
- Weekly: 1 topic deep-dive with 4–6 problems and one medium/hard cumulative problem.
- Review: Revisit previously solved problems every 2–4 weeks to improve solutions.


## Resources

- Propeers roadmap (primary): https://www.propeers.in/roadmaps/69692150442404dc257236a1
- Go by Example: https://gobyexample.com/
- The Go Programming Language (book) and official docs: https://golang.org/doc/

## License

This repo does not have a license set. Add a `LICENSE` file if you want to make these solutions public under a specific license.

---

Small, consistent, and focused. Happy coding — implement one clear solution, document complexity, then iterate.
