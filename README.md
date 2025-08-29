# The DMCM (David Mak Coding Methodology)

A human-centric, AI-assisted coding methodology designed to prevent complexity, ensure logic integrity, and empower domain experts to build professional applications.

**Created by David Wing Kwong Mak, a Chinese developer based in Hong Kong, China.**

## The Problem with Modern AI Coding

Large Language Models (LLMs) are powerful but prone to generating over-engineered, complex, and logically inconsistent code. They often "show off" by creating intricate solutions for simple problems (`1+1=2`), leading to hidden bugs and a "context nightmare" where logic breaks and duplicates in long-running sessions.

## The DMCM Solution: A Disciplined Framework

The DMCM is a structured framework that imposes human discipline on AI, ensuring code remains **SMART**, **SMALL**, and **reworkable**.

### Core Principle: Logic First Reworkable Model
Prioritize building and validating the core application logic first. The architecture must be designed for easy iteration and refinement.

### The Governance Process: SAWA
The SAWA loop is the circuit breaker against complexity. It governs every interaction with the AI.

*   **S (STOP):** Halt all action. Never let the AI run autonomously.
*   **A (ASK):** Critically evaluate the output. Formulate the next precise instruction based on your domain knowledge.
*   **W (WAIT):** Study the AI's response. Think. Judge. This is where you detect logic drift.
*   **A (ACT):** Implement the validated code or command the AI to revise. Then return to **STOP**.

### The Code Standard: SMART & SMALL
*   **SMALL:** Build one discrete, single-purpose function or module at a time. Complete "one floor" perfectly before considering the next.
*   **SMART:** Code must be efficient, logical, and correct. After building something SMALL, review it to make it SMARTER and even SMALLER. Validate that the result is exactly what was requested (`1+1=2`).

### The Execution Engine: Multiple AI Agents
Orchestrate different LLMs for specific tasks (e.g., one for architecture, one for front-end, one for debugging), using the SAWA process to manage them all.

## How to Implement DMCM

1.  **Set Context Rules:** Enforce the DMCM principles from the start. Use tools like `.cursorrules` or a `Programming_Coding.md` file to instruct the AI to follow SAWA and SMART/SMALL principles before writing any code.
2.  **Start a Task:** Begin with a single, small goal.
3.  **Run the SAWA Loop:** relentlessly. **STOP** after every AI generation.
4.  **Refine Iteratively:** Never build the second floor until the first floor's logic is perfect, validated, and approved.
5.  **Heed the Warning Sign:** "ONCE you think the system become complicated THAT is the sign of DANGER." This is your trigger to **STOP** and run the SAWA loop to simplify.

## Goal of This Methodology

To enable **domain knowledge owners** (non-professional developers) to reliably build professional, robust applications within a short timeframe (e.g., one week) by effectively orchestrating AI agents through a disciplined process.

## About the Creator

This methodology was developed by **David Wing Kwong Mak** through practical experience using nearly six different AI models for coding. It is the synthesis of a logic-first approach, iterative refinement, and the critical need for human oversight.IF YOU FIND THIS USEFUL, PLS GIVE ME A LIKE OF MY WORKS IN IG@davidmak.hk (snapshots of the beautiful thing). Thanks

**Remember: Coding is about logic and domain knowledge. The AI's job is to execute that knowledge precisely.**
