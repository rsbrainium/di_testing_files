# Lesson Knowledge Check & Challenge Solutions — Day 1

---

## Lesson 1 — Fairer Hiring with AI

### Knowledge Check — Inclusive language (after Section 1)

**Question:** "Why might 'recent graduate, digital native, high-energy' narrow your applicant pool even though none of those words names a protected characteristic?"

**Answer:** Each phrase acts as a *proxy* for a protected characteristic — "recent graduate" and "digital native" signal age, and "high-energy" can read as an ability or age cue. Qualified candidates who are older, returning to work, or work calmly may self-select out before they apply. Skill- and outcome-based wording keeps the bar high without sending those signals.

### 🚀 Lesson Challenge

**What was asked:** Draft and iteratively refine a Data Analyst job description, ask AI to flag exclusionary wording, then generate a 3-criteria rubric and one behaviour-based question per criterion.

**Example answer:**

A strong result iterates rather than accepting the first draft. The flagged-and-replaced wording resembles the XP solution (age/sameness proxies → skill-based language). A sample rubric:

| Criterion | Behaviour-based question |
|---|---|
| Analytical reasoning | "Tell me about a time data changed a decision your team was about to make." |
| Communication | "Describe explaining a complex finding to a non-technical colleague." |
| Collaboration | "Walk me through working with another team to get data you needed." |

The key marker of success: the questions ask for past behaviour ("tell me about a time…"), not self-rating.

---

## Lesson 2 — AI for HR Data and Documents

### Knowledge Check — Grounding (after Section "Working with files")

**Question:** "Why is an answer based on your uploaded handbook more trustworthy than the same question asked with no document attached?"

**Answer:** With grounding, the AI answers *from your approved document*, so the response reflects your actual policy rather than general patterns it learned elsewhere (which may be outdated, generic, or simply invented). It also makes the answer checkable — you can trace it back to the source you provided.

### 🚀 Lesson Challenge

**What was asked:** Have AI identify the top three improvement themes in an anonymised engagement survey, sharpen with one constraint, propose a three-month plan for the top theme, and note one privacy safeguard.

**Example answer:** Themes typically surface as communication, recognition, and workload/promotion visibility. A good constraint (e.g., "focus on remote employees") shifts the ranking and shows the student is directing the analysis. The plan should follow Month 1 Diagnose & Communicate → Month 2 Launch → Month 3 Measure. The privacy safeguard should mention keeping findings at theme level so no individual is identifiable, and not pasting PII into unapproved tools.

---

## Lesson 3 — From Prompts to Agents

### Knowledge Check — Prompt or agent? (after Section "What is an agent?")

**Question:** "You draft a different offer letter for each new hire, tailoring every one. Is that better served by a prompt or by an agent — and why?"

**Answer:** A **prompt.** The task is one-off and the context changes with every hire, so you want fresh drafting with your review each time. An agent earns its place when the same question recurs and consistency with policy matters — which a uniquely tailored letter does not.

### 🚀 Lesson Challenge

**What was asked:** Design an HR Policy Agent — a narrow purpose statement, three questions it answers and two it refuses/escalates, the single grounding source, and the escalation message.

**Example answer:**
- **Purpose:** "Answer routine employee questions about published HR policies using the official handbook."
- **Answers:** remote-work policy, parental-leave days, benefits enrolment dates.
- **Refuses + escalates:** exception requests, individual eligibility/pay questions.
- **Grounding:** the current Employee Handbook.
- **Escalation message:** *"This needs a person — I can't decide exceptions or individual cases. I've flagged it to HR, who'll follow up within one business day."*
