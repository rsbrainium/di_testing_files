# Solutions — ⭐ XP Exercises — Day 1: Prospecting with AI

---

## Exercise 1 — Scaffold a research prompt

### Question 1 — The scaffolded prompt

**Answer:**

A strong answer contains all three pillars plus an anti-hallucination constraint. Example:

> "You're helping me, a sales rep at Northwind Logistics. We sell freight-management software that reduces shipping errors and gives mid-size retailers real-time delivery visibility. My target account is Lumio Retail, a mid-size home-goods retailer that recently opened a second distribution warehouse. Give me a short bulleted brief covering: (1) recent company news, (2) likely operational challenges given their growth, and (3) possible decision-makers by function. Keep it under 200 words. Do not invent facts — if you're unsure about anything, say so and mark it as unverified."

| Element | Present? |
|---|---|
| Context (role + product + target) | ✅ — Northwind rep, product described, Lumio + warehouse |
| Clear task and output format | ✅ — bulleted brief, three specific items |
| Tone or length specified | ✅ — "under 200 words" |
| "Don't invent facts" constraint | ✅ — explicit, with "mark as unverified" |

**Why it's correct:** The prompt removes guesswork. The AI knows who it's helping, what's being sold, who the target is, and what "good" output looks like. The constraint is what makes it safe for sales — it pushes the model to flag uncertainty instead of producing confident fiction.

---

## Exercise 2 — Research brief + personalized opener

### Question 1 — Signals table

**Answer:**

A good submission treats *every* AI-surfaced fact as "verify before use." Example:

| # | Signal from research | Verify? | How you'd verify |
|---|---|---|---|
| 1 | Opened a second warehouse | Yes | Company news/press page, LinkedIn company posts |
| 2 | Likely decision-maker: VP of Operations | Yes | LinkedIn, company "About/Team" page |
| 3 | Reported delivery delays last peak season | Yes | Trade-press article, customer reviews |

**Why it's correct:** The point is the habit — there is no signal a careful rep would send to a buyer unchecked, because AI can hallucinate titles, dates, and events.

### Question 2 — Personalized opener

**Answer (example, built from the verified "second warehouse" signal):**

> "Congrats on opening the second distribution center — exciting growth. When retailers scale to a second warehouse, shipping errors and delivery-visibility gaps tend to spike before processes catch up. We've helped similar teams keep accuracy steady through that transition — worth a quick chat?"

**Why it's correct:** It references a specific, verified trigger, ties it to a problem Northwind actually solves, stays warm and brief, and ends with a low-pressure question — exactly the personalization pattern from the lessons.
