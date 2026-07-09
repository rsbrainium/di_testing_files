# AI for HR Data and Documents: Files, Forecasts, Compliance, and Privacy

### 👩‍🏫 👩🏿‍🏫 What You'll learn

- Work with uploaded files so AI answers from your documents (grounding)
- Use AI to forecast future skills and to scan compliance documents for risk
- Analyse engagement-survey data and turn it into a clear action plan
- Protect personal data (PII) and apply privacy rules like GDPR and CCPA

---

## Introduction

Most HR teams collect far more data than they have time to read: surveys, exit interviews, performance notes, vendor contracts, skills inventories. A generative AI assistant changes the economics of that backlog. Modern tools can read an uploaded spreadsheet, contract, or PDF and work directly with it — summarising, comparing groups, spotting risky clauses, and surfacing themes in seconds.

The skill that matters here is not "asking AI a question." It is **grounding**: giving the tool specific, approved documents to work from so its answers come from your policies and your data, not from general knowledge it picked up somewhere. Grounding is what separates a useful HR analysis from a confident-sounding guess. Everything in this lesson uses that idea, applied to four common jobs: planning ahead, reviewing compliance, reading engagement data, and doing all of it without mishandling people's personal information.

### 💼 Prerequisites

- Comfort opening a spreadsheet (Excel or Google Sheets) and recognising columns of data
- Awareness of what counts as confidential information in your organisation

### Useful Resources

| Resource | Link | Type |
|---|---|---|
| What's New in Microsoft 365 Copilot (May 2026) | https://techcommunity.microsoft.com/blog/microsoft365copilotblog/what%e2%80%99s-new-in-microsoft-365-copilot--may-2026/4522010 | Article |
| SHRM — The State of AI in HR 2026 | https://www.shrm.org/topics-tools/research/state-of-ai-hr-2026/full-report | Report |

---

## Working with files: grounding

Generative AI does not only respond to typed prompts — it can also read files you give it. You can upload a job description, a policy, or a survey, and the tool will reference that content as it works. Giving AI access to specific, approved documents so it answers from them is called **grounding**.

![How grounding works](images/grounding_flow.png)
*Grounding routes the AI through your approved sources, so the answer reflects your policy rather than a generic guess.*

Grounded tools can summarise an uploaded file, merge several inputs into one structured framework, and output results straight into Word or Excel. The practical upside: you stop copying and pasting between documents, and the AI's answers stay anchored to material you trust.

> **Knowledge Check — Grounding**
>
> *Think about:* "Why is an answer based on your uploaded handbook more trustworthy than the same question asked with no document attached?"
>
> *Quick activity (2 min):* Upload a short, non-sensitive document (a public job post is fine) to an AI tool and ask it to "summarise the key requirements in five bullet points." Notice that the summary stays inside the document you gave it.

---

## Planning ahead and reviewing compliance

**Strategic workforce planning** used to be retrospective — by the time a report arrived, priorities had shifted. AI makes it more forward-looking. It can scan labour-market signals (job postings, learning patterns, skill trends) and also read your own spreadsheets, such as a skills inventory, to compare current capabilities against future needs. You might prompt: *"What emerging skills will be most valuable for HR professionals over the next three years?"* and get a starting roadmap. Even partial data reveals useful patterns. The judgment about which skills fit your mission and budget stays with you.

**Compliance review** is a different kind of task. Here AI has to interpret legal language and obligations buried in long documents, not crunch numbers. You can paste or upload contract excerpts and prompt: *"Highlight compliance gaps in this document related to GDPR and SOC 2."* The tool flags missing or unclear terms — inconsistent data-retention windows, missing encryption commitments, ambiguous third-party access — and you can follow up with *"Explain the operational risk if this vendor lacks an encryption clause."* It can even produce an audit-ready summary: *"Summarise these compliance findings in a short report with sections for Risk, Action, and Owner."*

| Task | What AI is doing | What stays human |
|---|---|---|
| Workforce planning | Spotting skill trends across markets and your data | Choosing which skills to invest in |
| Compliance review | Flagging risky or missing clauses | Deciding legal sufficiency and acceptable trade-offs |

> 📌 **Common Misconception**
>
> *"If the AI says the contract is compliant, we're covered."*
>
> **Reality:** AI should highlight possible inconsistencies, not determine legal sufficiency. Final interpretation must come from your legal or compliance partners. The tool helps you focus their time, it does not replace their sign-off.

---

## Reading engagement data — and protecting people

AI assistants can open a file like `Engagement_Survey_2026.xlsx`, summarise the columns, compare groups, and suggest visualisations. You guide it with iterative questions: *"Compare engagement scores by department and summarise the top three improvement themes,"* then sharpen it with *"Focus only on managers' comments"* or *"Exclude neutral sentiment."* The quality of the analysis depends less on what the AI finds first and more on how precisely you direct its attention. Some tools also offer a reasoning or "thinking" mode that shows their working, which is useful for checking *how* a conclusion was reached, not just accepting it.

From insight you move to action. If employees cite "communication gaps" and "limited recognition," you can ask: *"Suggest engagement actions that address communication and recognition challenges,"* and structure the result as a simple three-month plan — Month 1 diagnose and communicate, Month 2 launch targeted initiatives, Month 3 measure and adjust.

All of this runs on personal data, so privacy is not an add-on. **PII** (Personally Identifiable Information) is anything that can identify an individual — names, performance scores, demographics. Regulations like **GDPR** in Europe and **CCPA** in California set strict rules on handling it, and using AI does not exempt you from them. Practical guardrails: anonymise data while you are exploring, only analyse data you have permission to use, use tools your IT or legal team approved for real data, and keep summaries broad enough that no single employee can be identified.

> **Real-World Example — Amazon's scrapped recruiting tool**
>
> Amazon built an experimental tool to score résumés, trained on a decade of mostly male applications. It taught itself to penalise the word "women's" and downgraded graduates of two all-women's colleges. Engineers could not make it reliably neutral, so Amazon scrapped it — a reminder that AI trained on past data can carry past bias forward.
>
> *Source: https://www.aclu.org/news/womens-rights/why-amazons-automated-hiring-tool-discriminated-against*

### Recommended Video

| Video | Duration | Why Watch |
|---|---|---|
| [HR Assistant Copilot using Copilot Studio](https://www.youtube.com/watch?v=OLNrA7GzzzU) | ~20 min | Demonstrates grounding an assistant in HR documents so it answers from approved sources rather than general knowledge. |

---

## 🚀 Lesson Challenge

You have an anonymised engagement survey for a mid-size company. In an AI tool:

**What to do:**
1. Describe the dataset to the tool (departments, an engagement score 1–5, and free-text comments) and ask it to identify the three strongest improvement themes.
2. Re-prompt with one constraint that sharpens the analysis (for example, "focus only on remote employees").
3. Ask it to propose a three-month action plan for the top theme, and write one sentence on how you would keep the analysis from identifying any individual.

*A brief solution for this challenge is available in the solutions file.*

---

## Key Takeaways

| # | Takeaway |
|---|---|
| 1 | Grounding — giving AI your approved documents — keeps answers anchored to your policies and data instead of generic guesses. |
| 2 | AI can forecast skills, flag compliance gaps, and surface engagement themes, but humans decide what to invest in and what is legally sufficient. |
| 3 | Never upload PII to unapproved tools; anonymise while exploring and follow GDPR/CCPA — using AI does not remove your privacy obligations. |
