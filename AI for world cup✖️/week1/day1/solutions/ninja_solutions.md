# Solutions — ⭐⭐⭐ Ninja Exercises — Day 1: AI for Human Resources

> This is one valid approach. Other well-reasoned answers are acceptable — the agent design should simply be narrow, grounded, and bounded, with a credible operating plan.

---

## Exercise 1 — Specify a safe HR Policy Agent

### Example specification

**Answer:**

| Section | Example specification |
|---|---|
| **Purpose (1 sentence) + why narrow** | "Answer Brightline employees' routine questions about published HR policies (leave, remote work, benefits enrolment, expenses) using the official handbook." Narrow scope is safer because every question maps to an existing, approved answer — there is no need for the agent to interpret or decide, which is where risk lives. |
| **Instructions (can / cannot)** | CAN: quote and summarise handbook policy, point to the relevant section, state enrolment windows and eligibility rules as written. CANNOT: approve requests, grant exceptions, interpret an individual's situation, give legal/tax advice, or comment on pay or performance. |
| **Grounding source(s)** | The current Employee Handbook and the Benefits Enrolment guide only — no general web knowledge. |
| **Boundaries (when to stop)** | Any question involving an exception, an individual's specific circumstances, interpretation of ambiguous policy, or a decision → stop and escalate. |
| **3+ questions it answers** | "What's our remote-work policy?"  ·  "How many days of parental leave do full-time employees get?"  ·  "When does benefits enrolment open?"  ·  "How do I submit an expense claim?" |
| **3+ questions it refuses + escalation message** | "Can I get an exception to the leave policy?"  ·  "Does this apply to my specific contract?"  ·  "Am I eligible for a promotion?"  ·  "How will my bonus be calculated?" — **Escalation message:** *"This one needs a person. I can't decide exceptions or individual cases — I've flagged your question to the HR team, and someone will follow up within one business day. Here's the relevant policy section in the meantime: [link]."* |
| **Operating & monitoring plan** | **Monthly 30-min review** of five checks: policy alignment (anything updated?), language drift (matches latest handbook?), edge cases (review the log), scope creep (handling things it shouldn't?), instruction accuracy. **Four signals tracked:** question volume, escalation rate, repeat questions, user feedback. **Day a policy changes:** update the agent's instructions *first*, test with realistic edge cases, and route affected questions to humans until it answers them correctly. Roll out over four weeks: test top 20 questions → pilot with 10–15 people → update → set review reminders. |

**Why this is a strong answer:** it leads with restraint — the "cannot" list and the boundary rule are more detailed than the "can" list, which is exactly the posture an employee-facing HR agent needs. The escalation message is neutral, sets a clear expectation, and still gives the employee something useful immediately. The operating plan treats the agent as something to maintain, not launch-and-forget, which is where drift problems start.
