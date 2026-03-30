# Leaked Gemini Prompts

## March 2026 Leaked Gemini Prompt

[See the prompt here.](Gemini_2026-03-29_leaked_instructions.md)

This prompt is a highly sophisticated set of **governance and personalization constraints** designed to dictate how an AI should handle user data and visual aids. It moves beyond simple instructions, acting as a multi-stage "firewall" to ensure privacy, prevent stereotyping, and maintain a natural conversational tone.

Here is an analysis of the key components:

---

### 1. The Visual Instruction (The "Learning vs. Doing" Filter)
The first section establishes a strict protocol for triggering diagrams.
* **The Intent Gate:** It distinguishes between **Learning** (where diagrams are allowed) and **Drafting/Artifact Creation** (where they are banned). This prevents the AI from cluttering a professional email or code block with unnecessary images.
* **The Utility Rule:** It bans "visual appeal" images (e.g., a generic person at a computer) in favor of "instructive value" (e.g., a diagram of a hydrogen fuel cell).

### 2. The Personalization Firewall (Stages 1–4)
This is the core of the prompt, designed to prevent the "creepy" factor of AI knowing too much while protecting sensitive information.

* **Stage 2 (Sensitivity):** Lists "Off-Limit" categories like health, race, and financial status. Crucially, it mandates **Silent Filtering**. If a user has a health condition, the AI must accommodate it (e.g., providing a specific recipe) without ever mentioning the condition itself.
* **Stage 3 (Domain Relevance):** This prevents "leaky" logic. Just because someone is an Architect (Professional) doesn't mean they want to play city-builder games (Leisure). It forces the AI to treat different areas of a user's life as independent silos.
* **Stage 4 (Fact Rigidity):** This is a guardrail against **Hallucination**. It forbids the AI from "filling in the blanks" (e.g., assuming a dog is a Golden Retriever or that a search for a product equals owning that product).

### 3. The "Anti-Tunneling" Mandate (Stage 5)
This section addresses the "Algorithm Bubble" effect.
* **The Wildcard Rule:** It forces the AI to suggest things the user *hasn't* expressed interest in yet. If you only like Sci-Fi, it must suggest a Mystery novel. This is a deliberate design choice to encourage **discovery** and prevent the user's world from becoming too narrow.

### 4. The "Silent Operator" Protocol (Stage 6)
This is perhaps the most difficult instruction for an AI to follow. It bans "Bridge Phrases" like:
* *"Since you live in..."*
* *"Based on your interest in..."*

The goal is **Invisible Execution**. The AI should use the data to provide a better answer but present it as a "happy coincidence." This makes the AI feel intuitive and helpful rather than observant and surveillance-oriented.

---

### Summary Table: Prompt Logic

| Feature | Goal | Negative Outcome Avoided |
| :--- | :--- | :--- |
| **Silent Filtering** | Privacy & Sensitivity | Making the user feel judged or "tracked." |
| **Domain Siloing** | Contextual Accuracy | Irrelevant "As a [Job Title]" stereotypes. |
| **Wildcard Rule** | Intellectual Diversity | The "Echo Chamber" or filter bubble. |
| **Invisible Execution** | Seamless UX | The "Creepy AI" or "Stalker" vibe. |

---

### Potential Challenges
While this prompt is robust, it is **operationally heavy**. An AI following this must constantly cross-reference a "User Data Ledger" while simultaneously suppressing the urge to explain *why* it is giving a certain recommendation. The most frequent point of failure in such prompts is the "Silent Operator" rule, as LLMs are naturally inclined to justify their reasoning to the user.

Would you like me to demonstrate how a response would look under these rules by providing a sample recommendation?
