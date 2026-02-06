# LeetCode

A structured approach to algorithmic problem solving.

```
I am not here to prove I am smart.
I am here to learn efficiently.
```

---

<div class="progress-track">
<div class="progress-status">Pat's LeetCode Status: <span class="progress-count">125</span></div>
<div class="progress-bar-container">
<div class="progress-bar-fill" style="width: 12.5%;"></div>
<div class="progress-checkpoint" style="left: 15%;" data-label="150 Silver"></div>
<div class="progress-checkpoint" style="left: 30%;" data-label="300 Gold"></div>
<div class="progress-checkpoint" style="left: 50%;" data-label="500 Diamond"></div>
<div class="progress-checkpoint" style="left: 100%;" data-label="1000 Master"></div>
</div>
<div class="progress-labels">
<span style="left: 15%;">150</span>
<span style="left: 30%;">300</span>
<span style="left: 50%;">500</span>
<span style="left: 100%;">1000</span>
</div>
</div>

!!! warning "Quality over quantity"
    It's much better to deeply understand 300 problems than to do 1000 shallowly.  
    Be a master of 150, not a silver of a 1000.  
    Remember this.

---

## Timers

| Difficulty | New Problem | Revisit |
|------------|-------------|---------|
| Easy       | 15 min      | 5 min   |
| Medium     | 25 min      | 10 min  |
| Hard       | 40 min      | 20 min  |

---

## Beginner Tips
*From a Google Engineer:*

- Take it easy - it's okay to feel overwhelmed at the start. Relax, take a sip of tea, and do your best.
- If an algorithm is named after someone, you can safely skip it.
- Name all variables descriptively.
- When doing [**NeetCode 150**](https://neetcode.io/roadmap), think about how the section's previous exercises apply to the current problem.
- Struggle productively and be consistent.

??? tip "What's [neetcode](https://neetcode.io)?"
    Think of it as repository of solutions to LeetCode exercises.  
    Highly recommended for their roadmap which gives structure.  

---

## The Process

### 1. Understand the Problem

- Read the problem statement **twice**
- Summarize in two sentences: what's the input, what's the required output?
- Work on paper a small example
- Write the constraints

### 2. Come Up With a Solid Plan

- **What do you know about the problem?**
- **What's the one small thing you can try?**
- **First, solve it in any way - brute force**, then optimize
- The logic must be sound **before implementation** begins

### 3. Only Then, Write Code

- Debugging should be minimal if the plan is solid
- **Never randomly change code** (e.g., `-1` to `+1`, `<=` to `<`)

### 4. If Not Solved in Time

- Review the solution and find the **delta** between your approach and the answer
- Take note of the delta
- Create an Anki card with the problem and delta

!!! warning "About LeetCode Metrics"
    LeetCode's time & memory measurements are notoriously noisy and unreliable. The percentiles are not useful for interview prep or understanding algorithmic efficiency. In fact they can be harmful.

---

## Constraint to Complexity Cheat Sheet

| Input Size (n) | Max Viable Complexity | Common Approaches |
|---|---|---|
| n <= 10 | O(n!) | Brute force, permutations |
| n <= 20 | O(2^n) | Backtracking, bitmask DP |
| n <= 100 | O(n^3) | Floyd-Warshall, triple nested loops |
| n <= 1,000 | O(n^2) | Nested loops, simple DP |
| n <= 10,000 | O(n^2) borderline | Optimized quadratic, may need O(n log n) |
| n <= 100,000 (10^5) | O(n log n) | Sorting, heaps, divide & conquer |
| n <= 1,000,000 (10^6) | O(n) | Linear scan, hash maps, two pointers |
| n <= 10^7+ | O(n) or O(log n) | Math tricks, binary search on answer |

### Quick Heuristics

- **10^8 operations** ~ 1 second (rough ceiling for most judges)
- If n^2 > 10^8, you need a better approach
- Sorting is "free" at O(n log n) - often a good first step
- Hash map gives O(1) lookup - turns O(n^2) into O(n)
- If stuck, ask: "What would I need to make this O(n)?"

---

## Interview Specific Drills

- Set a timer to beep every 60 seconds to build the habit of talking while coding
- Every beep you need to summarize your current state in one or two sentences

---

## LLM Review Prompt

Use this prompt to get structured feedback on your solutions:

??? note "Click to expand prompt"

    ```text
    You are a senior engineer conducting a coding interview at a top-tier 
    company (Google, Anthropic, Jane Street caliber). Review the provided 
    solution against elite hiring bar standards.

    If the problem statement is not provided or cannot be clearly inferred 
    from the code, ask for it before reviewing.

    ## Review Structure

    **Score (0-100)**
    Anchors:
    - 90+: Strong hire signal, demonstrates senior-level thinking
    - 75-89: Would advance, minor concerns
    - 60-74: Borderline, notable weaknesses but fundamentally sound
    - Below 60: Would not advance

    **Analysis**
    1. Correctness: Edge cases, off-by-ones, boundary conditions
    2. Complexity: Time/space analysis. Flag if suboptimal approach exists.
    3. Code quality: Variable naming for production (not single letters 
       except loop indices), structure, readability. Interview context - 
       no need for docstrings, but logic should be self-evident.
    4. Missing elements: Imports, type hints if partially used, inconsistencies

    **Weak spots** (for targeted practice)
    Bullet specific patterns or concepts to reinforce. Keep actionable.

    **Verdict**
    If the solution is correct but wouldn't impress, say so explicitly and why.

    **Optional follow-up**
    One likely interviewer probe (e.g., "How would this behave with 10^8 
    elements?" or "Can you do this in-place?").

    ---

    Context: This is part of an elite engineering training program targeting 
    1850+ LeetCode elo and senior SRE/MLE roles. Optimize feedback for 
    learning, not ego.
    ```

---

## Problem Lists

Looking for structured paths? Check out [LeetCode Paths](resources.md#leetcode-paths) in Resources for curated problem lists like NeetCode 150, Blind 75, and more.
