#  Bloomberg 2027 Software Engineering Prep Compendium

> **Target:** Bloomberg 2027 New Grad Software Engineer (Rounds 1–3)  
> **Evaluation Bar:** Strong Hire  
> **Rubric Alignment:** Official Bloomberg Engineering Workshops (*5-Stage System Design Framework* & *6-Step Debug Loop*)

---

### Overview & Repository Purpose
A collaborative preparation repository containing production-grade prompts, verified workshop rubrics, and technical architectures for the Bloomberg 2027 SWE loops:

* **Rounds 1 & 2 (AI-Assisted Codebase Navigation & Debugging):** 
  * Strict execution of the **6-Step Debug Loop**: `Spec Claim ➔ Suspect Code ➔ Hypothesis ➔ Verbal Explanation ➔ Forced-Source Unit Test (RED) ➔ Minimal Patch (GREEN)`.
  * Domain modeling rigor: integer cents (`balance_cents`, `pot_cents`), frozen immutable snapshots (`@dataclass(frozen=True)`, `tuple`), and deterministic state machine `Enum` types.
  * Prompt discipline playbooks (permitted accelerators vs. disqualifying query traps).

* **Round 3 (Open-Ended System Design):**
  * Bloomberg's **5-Stage Blueprint**: `01. Clarify ➔ 02. Interactions (APIs First) ➔ 03. Identify Data (Relational Schemas) ➔ 04. Simple 3-Tier Design ➔ 05. Challenge & Improve (Trade-Offs)`.
  * Complete technical breakdowns for all **7 Bloomberg Question Bank Archetypes** (Room Booking, Holiday Service C++ SDK, Real-Time VWAP Analytics, Build Cache, Financial Web App, Kafka/Distributed Commit Log, and Trending News Feed).

* **Tooling Prompts:** 
  * Ready-to-use simulator prompts for Claude (Sonnet), ChatGPT, and IDE coding agents (Antigravity/Cursor) to generate multi-file codebases with subtle spec violations.
