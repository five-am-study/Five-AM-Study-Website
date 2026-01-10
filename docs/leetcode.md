# LeetCode

A structured approach to algorithmic problem solving.

---

## Beginner Tips 
*From a Google Engineer:*

- Take it easy - it's okay to feel overwhelmed at the start. Relax, take a sip of tea, and do your best.
- If an algorithm is named after someone, you can safely skip it.
- Name all variables descriptively.
- When doing [**NeetCode 150**](https://neetcode.io/roadmap), think about how the section's previous exercises apply to the current problem.
- Struggle productively and be consistent.

---

## The Process

### 1. Understand the Problem

- Read the problem statement **twice**
- Summarize in two sentences: what's the input, what's the required output?
- Enumerate:
    - 3 edge cases (if possible)
    - Input/output constraints
- Calculate the **Complexity Budget**: given the constraints, what's the worst complexity that would pass?

??? tip "What's neetcode?"
    Think of it as repository of solutions to LeetCode exercises.  
    Highly recommended for their roadmap which gives structure.  

### 2. Plan Before Coding

- **Review known patterns** - which applies here and why?
- **Solve it any way first** (brute force), then optimize
- **Write pseudocode** for the algorithm
- Logic must be sound **before implementation** begins

### 3. Write Code

- Write imports first
- Debugging should be minimal if the plan is solid
- **Never randomly change code** (e.g., `-1` to `+1`, `<=` to `<`)

### 4. If Not Solved in Time

- Review the solution and find the **delta** between your approach and the answer
- Take note of the delta
- Create an Anki card with the problem and delta

!!! warning "About LeetCode Metrics"
    LeetCode's time & memory measurements are notoriously noisy and unreliable. The percentiles are not useful for interview prep or understanding algorithmic efficiency. In fact they can be harmful.

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
    1850+ LeetCode elo and senior SWE roles. Optimize feedback for 
    learning, not ego.
    ```

---

## Problem Lists

Looking for structured paths? Check out [LeetCode Paths](resources.md#leetcode-paths) in Resources for curated problem lists like NeetCode 150, Blind 75, and more.
