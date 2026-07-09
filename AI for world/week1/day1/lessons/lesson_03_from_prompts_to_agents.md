# From Prompts to Agents: Building and Operating Safe HR Assistants

### 👩‍🏫 👩🏿‍🏫 What You'll learn

- Tell the difference between a one-off prompt and a persistent agent
- Apply the four design choices that keep an HR agent safe
- Recognise why employee-facing agents raise the stakes, and where to set boundaries
- Operate an agent after launch with a simple monthly review

---

## Introduction

So far, the work has been prompt-based: you ask, the AI answers, you review. That fits one-off tasks where the context changes each time — drafting a posting, analysing a survey, reviewing a contract. But a lot of HR work is not like that. The questions repeat, the answers already exist in your handbook, and consistency matters more than creativity.

Picture an employee asking, "How many days of parental leave do I get as a part-time employee?" Without help, they search the intranet, find nothing clear, and email HR — and wait two days. With an HR policy agent, they ask directly and get an accurate, handbook-sourced answer in seconds; if the case is complex or needs an exception, the agent hands them to a human. That is the shift this lesson is about: knowing when to move from prompting to a scoped, persistent assistant, and how to build one that stays safe.

### 💼 Prerequisites

- You are comfortable writing and refining prompts in a chat tool
- You understand grounding — pointing AI at approved source documents

### Useful Resources

| Resource | Link | Type |
|---|---|---|
| Copilot Agents: From Prompts to Agents (Microsoft) | https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/copilot-agents-from-prompts-to-agents/4465332 | Article |
| How Do AI Agents Work? (Microsoft Copilot) | https://www.microsoft.com/en-us/microsoft-copilot/copilot-101/how-do-ai-agents-work | Documentation |

---

## What is an agent?

An agent is a persistent assistant designed for a specific, recurring task. The difference from prompting is like giving someone directions every time they ask versus hiring a guide who knows the route and can help anyone. With prompts, each interaction starts fresh and you supply the context. With an agent, you define the rules once — instructions, approved sources, and limits — and from then on it behaves consistently without you restating anything.

![Prompt versus agent](images/prompt_vs_agent.png)
*A prompt is a conversation; an agent is a service desk. Agents are not more powerful than prompts — they are more consistent and more tightly scoped.*

Agents are not inherently smarter than prompts. Their value is consistency and scope, and that becomes critical when several people need the same kind of help, responses must match official policy, and mistakes could create confusion or risk.

> **Knowledge Check — Prompt or agent?**
>
> *Think about:* "You draft a different offer letter for each new hire, tailoring every one. Is that better served by a prompt or by an agent — and why?"
>
> *Quick activity (2 min):* List two HR questions your team answers the same way every week. Those are agent candidates. List one task that changes every time. That is a prompt task.

---

## The four building blocks

When you design an agent you are shaping behaviour, not just asking for output, so a few design choices matter more than they did with prompts.

![The four building blocks of a safe HR agent](images/agent_building_blocks.png)
*Purpose, instructions, grounding, and boundaries — the four choices that keep an HR agent predictable and safe.*

| Block | What it means |
|---|---|
| **Purpose** | A narrow, well-defined role. In AI and HR, narrower is usually safer. |
| **Instructions** | Be explicit about what it can and cannot do. Vague instructions cause unpredictable behaviour. |
| **Grounding** | Rely only on approved sources — official policy documents, not general knowledge. |
| **Boundaries** | When a question involves exceptions, interpretation, or decisions, stop and redirect to a human. |

This is why employee-facing agents deserve extra care. When HR uses AI internally, a human catches anything off before it reaches anyone. When an agent talks directly to employees, responses land immediately, and people tend to read them as authoritative because they come from an official system.

Career questions are the clearest example of high stakes. A Career Coach–style agent can help an employee identify skills to develop, learn about common paths, and frame development goals — acting as a thinking partner. But there are lines it should never cross: it should not recommend promotions, give compensation advice, interpret performance evaluations, or replace a conversation with a manager. Those need human judgment and accountability.

> **Real-World Example — HR policy agents in practice**
>
> Microsoft's own guidance walks through building an HR policy advisor that answers handbook questions and escalates anything requiring interpretation, illustrating the purpose/grounding/boundaries pattern in a real tool.
>
> *Source: https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/copilot-agents-from-prompts-to-agents/4465332*

> 📌 **Common Misconception**
>
> *"A more advanced model automatically means a more trustworthy agent."*
>
> **Reality:** Trust in employee-facing AI comes from design choices — clear boundaries, transparent escalation, visible human accountability — not from how powerful the underlying model is. A simple, well-scoped agent beats a clever, unbounded one.

---

## Operating an agent after launch

Launch day is not the finish line. Once people rely on an agent, its guidance becomes part of how work gets done, and that is when operational responsibility begins. Problems rarely announce themselves; instead you see patterns — the same questions recurring, employees double-checking answers, small inconsistencies. The usual culprit is **drift**: policies change while the agent's instructions stay the same, so its answers quietly go stale.

![The 30-minute monthly review](images/monthly_review.png)
*A short monthly review catches drift before it compounds. This is maintenance, not a project.*

A simple operating rhythm keeps things healthy. Run a 30-minute monthly review across the five checks above. When a policy changes, update the agent's instructions *first* — before employees start asking — and test with realistic edge cases; if it can't handle them, narrow its scope or route those questions to humans until you can fix it properly. Track four signals over time: question volume, escalation rate, repeat questions, and user feedback. And when something goes wrong, fix the configuration, document what changed, and tell affected employees plainly: "We noticed the system gave outdated guidance about X; here's the current policy." Transparency repairs trust; silence erodes it.

### Recommended Video

| Video | Duration | Why Watch |
|---|---|---|
| [How to Build an HR Copilot AI Agent — Step-by-Step, by a Microsoft Engineer](https://www.youtube.com/watch?v=488C_3gNlRQ) | ~25 min | Walks through purpose, grounding, and boundaries while building a real HR agent end to end. |

---

## 🚀 Lesson Challenge

Your company wants an **HR Policy Agent** that answers handbook questions (leave, remote work, benefits enrolment).

**What to do:**
1. Write a one-sentence purpose statement that keeps the role narrow.
2. List three questions the agent should answer and two it must refuse and escalate.
3. Name the single approved source it should be grounded in, and write the escalation message it shows when it hits a boundary.

*A brief solution for this challenge is available in the solutions file.*

---

## Key Takeaways

| # | Takeaway |
|---|---|
| 1 | Use a prompt for one-off, changing tasks; build an agent when the same question recurs and consistency with policy matters. |
| 2 | Four design choices keep an HR agent safe: a narrow purpose, explicit instructions, grounding in approved sources, and boundaries that redirect to a human. |
| 3 | Agents need maintenance — a short monthly review catches drift, and transparency after a mistake is what preserves employee trust. |
