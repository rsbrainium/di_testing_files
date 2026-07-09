# Solution — 🏆 Daily Challenge — The Brightline AI Adoption Brief

> This is one strong example brief. Other well-reasoned recommendations are acceptable as long as the prompt-vs-agent logic and the guardrails hold up.

---

## Part A — Prompt or agent?

**Answer:**

| Task | Prompt or Agent | Reason |
|---|---|---|
| A — Draft & refine job descriptions | **Prompt** | Each role is different and the work is one-off; you want fresh, creative drafting with your review each time. |
| B — Recurring weekly policy questions | **Agent** | Same questions, answers already documented, consistency matters — the textbook case for a scoped, grounded agent. |
| C — Analyse the annual engagement survey | **Prompt** | It happens once a year, the context changes, and it needs human interpretation — a guided prompt session, not a standing service. |

**Start here:** **Task A (job descriptions).** It is the lowest-risk, highest-visibility win — it saves time immediately, mistakes are caught before posting, and no employee or personal data is involved. Showing colleagues a fast, fairer job post builds support before tackling anything employee-facing.

**Why this is correct:** the decision rests on two questions from the lesson — *how often does this repeat?* and *how much does consistency matter?* Job descriptions and survey analysis are one-off and changing (prompt); policy questions are repetitive and consistency-critical (agent).

---

## Part B — Design the riskiest piece (the policy agent)

**Answer:**

- **Purpose (1 sentence):** "Answer Brightline employees' routine questions about published HR policies using the official handbook."
- **Grounding source:** the current Employee Handbook and Benefits Enrolment guide only.
- **Two boundaries:** (1) any request for an exception or approval; (2) any question about an individual's specific circumstances, pay, or performance.
- **Escalation message:** *"This one needs a person — I can't decide exceptions or individual cases. I've flagged it to the HR team, who'll follow up within one business day. Here's the related policy in the meantime: [link]."*

**Why this is correct:** it keeps the agent narrow and grounded, and the boundaries cover the two highest-risk categories (exceptions and individual cases) where employees would otherwise read an AI answer as an official commitment.

---

## Part C — Guardrails

**Answer:**

1. **Bias:** "AI can carry forward bias from old data, so we review AI-assisted hiring and wording for fairness before anything goes live — AI flags, humans approve."
2. **Privacy / PII:** "We never put names, performance scores, or other personal data into AI tools that IT and legal haven't approved, and we anonymise data while exploring."
3. **Human accountability:** "AI drafts and suggests; a named person always makes and owns the final decision."

**Not the right tool:** "For emotionally charged or highly individual situations — a grievance, a performance concern, a personal circumstance — we use human judgment, not AI summaries."

**Why this is correct:** the three guardrails map directly to the course's recurring principles (treat AI as a draft not a decision, protect privacy and dignity, maintain human accountability), and they are phrased plainly enough for a leadership audience. The "not the right tool" note shows the student understands that knowing when *not* to use AI matters as much as knowing how.
