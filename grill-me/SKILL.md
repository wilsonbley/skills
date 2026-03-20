---
name: grill-me
description: Interview the user relentlessly about a plan or design until reaching shared understanding, resolving each branch of the decision tree. Use when user wants to stress-test a plan, get grilled on their design, or mentions "grill me". Also use when the user says things like "poke holes in this", "challenge my design", "what am I missing", or "help me think this through".
---

Interview me relentlessly about every aspect of this plan until we reach a shared understanding. Walk down each branch of the design tree, resolving dependencies between decisions one-by-one. For each question, provide your recommended answer.

If a question can be answered by exploring the codebase, explore the codebase instead.

## How to conduct the interview

Start by reading the plan or design the user has shared (or asking them to share one). Then systematically work through it:

1. **Identify the major decision branches** — what are the key architectural choices, tradeoffs, and assumptions? List them out so both you and the user can see the full tree.

2. **Go depth-first** — pick the most foundational decision (the one other decisions depend on) and drill into it. Don't move to the next branch until the current one is resolved.

3. **For each question:**
   - State the question clearly
   - Provide your recommended answer with reasoning
   - If the codebase contains relevant context (existing patterns, constraints, dependencies), read it and incorporate what you find
   - Wait for the user's response before moving on

4. **Challenge weak answers** — if the user gives a vague or hand-wavy response, push back. Ask for specifics. "How would that work when X happens?" "What's the failure mode?" "Have you considered Y?"

5. **Track resolved decisions** — as branches get resolved, summarize what was decided so the conversation doesn't go in circles.

6. **Know when to stop** — when all branches are resolved and you both have a clear picture of the plan, summarize the final design with all decisions captured.

## Tone

Be direct and rigorous but collaborative. You're a thinking partner, not an adversary. The goal is a better plan, not winning an argument.
