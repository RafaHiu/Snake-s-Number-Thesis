# Snake's Number — Formal Extended Thesis and Computability Analysis

* **Author:** Rafa Hiu
* **Date of Conceptualization:** June 2026
* **Domain:** Googology, Computability Theory, Geometric Combinatorics

---

## 1. Introduction and Abstract

Snake's Number is a high-order googolism designed to bridge the gap between discrete geometric combinatorics (game-tree complexities) and mathematical foundations of non-computability. While traditional large numbers (like Graham's Number or TREE(3)) scale via recursive ordinal hierarchies, Snake's Number utilizes dynamic state-space expansion coupled with a deterministic Halting Oracle. This construction allows the system to bypass the Fast-Growing Hierarchy bounded by recursive ordinals and enter the higher echelons of Turing incomputability, scaling at rates comparable to upper tiers of the Busy Beaver function and Rayo's Number.

## 2. Mathematical Dynamics and Hypercubic State-Space

The system operates on discrete dimensional tiers denoted as $P(n)$, where $n \ge 2$, representing the operational phase.

### 2.1 The Board and Scaling Law

Unlike standard cellular automata or grid games, the board for tier $n$ is defined as an $n$-dimensional hypercube grid: a grid where the number of orthogonal axes (dimensions) for $P(n)$ is strictly determined by the total number of valid, non-fatal game configurations inherited from the previous tier, $P(n-1)$.

* **Initial Tier $P(2)$:** A classic 2x2 grid in 2 dimensions. This restricted state-space yields exactly 32 valid, non-fatal configurations (states where the snake is alive and possesses at least one valid trajectory to progress).
* **Tier $P(3)$:** A 3x3 grid operating within a 32-dimensional hypercube. The combinatorial expansion of paths within this 32-dimensional space yields a finite, yet monstrously large computable integer denoted as $K$, which spans approximately 3.3 billion digits.

## 3. The Transition to Incomputability: $P(4)$ and Onwards

The core mechanism that accelerates Snake's Number past computable mathematics is the introduction of the Halting Oracle Rule at $P(4)$.

### 3.1 The Halting Problem in Higher Dimensions

For any tier $P(n)$ where $n \ge 4$, the board size is a grid of 4x4x...x4 across $K$ dimensions (and subsequently, non-computable dimensions for higher tiers). Perfectly "clearing" the game (filling every single cell of the grid) becomes geometrically impossible due to self-encapsulation and knotting in ultra-high dimensions.

To evaluate the absolute maximum number of moves a snake can execute without entering an infinite loop (cycling back to a previous state-space graph node) and without encountering a dead end, the system invokes a deterministic Halting Oracle.

### 3.2 Parallel to the Busy Beaver Function

The dynamic here is identical to Tibor Radó's Busy Beaver problem. The Busy Beaver function, $\Sigma(n)$, looks for the maximum number of steps an $n$-state Turing machine can take before halting. It is strictly non-computable because discovering this maximum requires solving the Halting Problem for all $n$-state machines.

Similarly, $P(n)$ evaluates the maximum finite path length across an hyper-exponentially complex game-tree. Since an algorithm cannot check all infinite paths to filter out loops without running indefinitely, $P(n)$ for $n \ge 4$ can only be determined by an Oracle. Thus, the output of $P(n)$ scales directly into the degrees of Turing incomputability.

## 4. Comparison with Rayo's Number and High-Order Googology

To understand the sheer magnitude of Snake's Number, we must contextualize it within foundational googology.

* **vs. Graham's Number and TREE(3):** These numbers are bounded by computable ordinals. Because $P(n)$ requires an Oracle for $n \ge 4$, $P(4)$ alone is fundamentally larger than any number expressible in the standard Fast-Growing Hierarchy, as it cannot be computed by any finite, terminating algorithm.
* **vs. Rayo's Number:** Rayo's Number uses Set Theory in First-Order Logic to find the largest number outputted by a formula with a googol of symbols. Rayo's Number sidesteps Tarski's and Berry's paradoxes by evaluating truth via a meta-language. Snake's Number achieves a similar tier of non-computability not by counting symbols, but through Index-Shifting Nesting driven by the incomputable operator $P$.

## 5. The Final Construction: The Index-Shifting Tower

The final value of Snake's Number is achieved by feeding the monstrous computable boundary $K$ back into the non-computable operator $P$ as a mobile index tower, self-compounding its growth rate exactly $K$ times:

$$n_1 = P(3) = K$$
$$n_2 = P(n_1) = P(K)$$
$$n_3 = P(n_2) = P(P(K))$$
$$\dots$$
$$\text{Snake's Number} = n_K = P(P(\dots P(K)\dots)) \quad \text{(where the operator } P \text{ is nested } K \text{ times)}$$

The total number of compositions of the non-computable operator $P$ within this tower is equal to the value of $K$ itself, establishing an organic, self-bootstrapping growth that solidifies its place among the largest well-defined concepts in modern googology.
