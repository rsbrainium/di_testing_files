# Solutions — ⭐⭐⭐ Ninja Exercises — Day 1: Prospecting with AI

> This is one valid approach. Other well-reasoned answers are acceptable — Ninja exercises are open-ended, and a different workflow can be equally strong if the verification logic is sound.

---

## Exercise 1 — Design the prospecting playbook

**Example answer:**

### Northwind AI-Assisted Prospecting Playbook

| Step | Goal | Scaffolded AI prompt (summary) | Human verification before next step |
|---|---|---|---|
| 1. Account snapshot | Understand the company fast | "You're helping a Northwind rep. Summarize [company]: size, industry, recent news. Don't invent facts; flag unverified items." | Confirm company size and any cited news against the company site |
| 2. Find signals | Spot trigger events | "List recent trigger events for [company] — funding, hires, expansion, launches — with the source for each." | Open each source link; drop any with no real source |
| 3. Map decision-makers | Reach the right person | "Who are likely decision-makers in [function] at [company], by role?" | Verify names/titles on LinkedIn before contacting |
| 4. Pick the angle | Choose the strongest trigger | "Given these signals, which is most relevant to freight-management software, and why?" | Sanity-check the AI's reasoning against the product fit |
| 5. Draft openers | Personalize per persona | "Write a 2–3 sentence opener for [persona] referencing [verified trigger]. Warm, specific, soft CTA." | Edit into the rep's own voice; confirm every fact referenced is verified |
| 6. Final check | Ship safely | — | Read aloud; confirm no unverified claim, no wrong title, no stale date |

### Guardrails (failure modes + checks)

| Failure mode | Check that catches it |
|---|---|
| AI invents a job title or names the wrong person | Verify every contact on LinkedIn / company team page before outreach |
| AI cites an outdated or invented funding/news figure | Require a source link for every signal; open it; drop unsourced claims |
| AI states a competitor or pricing claim that isn't true | Never reference competitor specifics unless confirmed from a primary source |
| Opener references an event that didn't happen | Confirm the trigger event from two angles before it appears in a message |

### Speed vs. accuracy note

> **Move fast:** Step 1 (account snapshot) — a rough, quick summary is fine because nothing here reaches the buyer yet; it just orients the rep.
>
> **Verification is non-negotiable:** Step 5–6 (anything in the actual message). Once a fact is in an email to a prospect, an error costs trust you can't easily recover. The cost of being wrong is highest at the point of contact, so that's where the human check is mandatory.

**Why it's correct:** A strong playbook is repeatable (a new rep could follow it), uses scaffolded prompts at each step, and — crucially — places explicit human verification between the AI's output and the buyer. It also reasons about *where* speed is acceptable versus where accuracy must win, which is the core judgment the exercise tests.
