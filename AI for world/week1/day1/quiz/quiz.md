# Day 1 Quiz: AI for Human Resources

Test your understanding of today's topics: using AI for fairer hiring, working with HR data and documents (grounding, compliance, privacy), and knowing when to move from one-off prompts to persistent agents.

---

## Questions

### Easy

**1. A recruiter pastes a job ad into an AI tool, which suggests replacing "high-energy digital native" with "comfortable working with data tools." Why is the suggestion an improvement?**

A) The new phrase is shorter, so the ad loads faster
B) "Digital native" is illegal to use in any job ad worldwide
C) The original phrase acts as a proxy for age, which can discourage qualified applicants
D) AI always writes more professional language than humans

---

**2. An HR manager asks an AI tool to suggest a salary range for a new role. What is the right way to use that number?**

A) As a research starting point, validated against the company's own pay framework and local rules
B) As the final salary, since the AI used real market data
C) Ignore it — AI cannot know anything about salaries
D) Publish it immediately to show salary transparency

---

**3. An employee asks an HR Policy Agent, "Can I get an exception to the leave policy for my situation?" What should a well-designed agent do?**

A) Invent a reasonable-sounding exception to be helpful
B) Stop and redirect the employee to a human in HR
C) Approve the exception if the request seems fair
D) Refuse to respond and close the conversation with no explanation

---

### Medium

**4. A team uploads last year's mostly-male engineering résumés to train an AI screening model. Based on today's lessons, what is the most likely risk?**

A) The model will be too slow to be useful
B) The model will refuse to score any résumés
C) The model will recommend paying everyone the same salary
D) The model will learn to favour male-associated patterns and carry past bias forward

---

**5. An HR analyst wants AI to answer questions strictly from the company's own handbook, not from general internet knowledge. Which approach achieves this?**

A) Asking the question several times until the answers agree
B) Grounding the AI by uploading the approved handbook and having it answer from that document
C) Turning on the tool's web-search feature
D) Using a more advanced AI model

---

**6. HR wants to summarise engagement-survey comments with AI. Which practice best protects employees?**

A) Keep findings at the theme level and use anonymised data so no individual can be identified
B) Quote the three most emotional individual comments verbatim in the report
C) Upload the raw file with names to whichever AI tool is fastest
D) Skip privacy steps because survey data isn't really personal

---

### Harder

**7. Brightline does three things: drafts a different job ad for each open role, answers the same five policy questions every week, and runs one annual engagement analysis. Which split between prompts and agents fits best?**

A) All three should be agents, for maximum automation
B) All three should be prompts, since AI can't be trusted to run alone
C) Job ads = prompt, weekly policy questions = agent, annual analysis = prompt
D) Job ads = agent, weekly policy questions = prompt, annual analysis = agent

---

**8. An HR Policy Agent that worked perfectly at launch starts giving slightly outdated answers three months later, even though nothing "broke." What happened and what is the fix?**

A) The AI model became less intelligent; switch vendors
B) Employees asked too many questions; limit usage
C) The agent was hacked; reset all passwords
D) Policies changed while the agent's instructions stayed the same (drift); update its instructions first and test edge cases

---

**9. A Career Coach–style agent is asked, "Based on my reviews, am I ready for promotion?" What is the safest, best-designed response?**

A) Estimate a promotion readiness percentage from the employee's review text
B) Decline to judge readiness and redirect the employee to their manager or HR
C) Recommend the employee apply, to be encouraging
D) Interpret the performance reviews and list reasons for and against

---

## Answer Key

**1. C) The original phrase acts as a proxy for age, which can discourage qualified applicants**
Phrases like "digital native" and "high-energy" don't name a protected characteristic, but they signal one — which is exactly why they slip past review and narrow the pool. The fix is skill-based wording. Option B is false (the phrase is not universally illegal), and A and D miss the fairness point entirely.

**2. A) As a research starting point, validated against the company's own pay framework and local rules**
AI salary benchmarks speed up research but don't account for your internal equity, framework, or pay-transparency obligations. B over-trusts the tool, C under-uses it, and D skips the human validation the lesson stresses.

**3. B) Stop and redirect the employee to a human in HR**
Exceptions involve interpretation and decisions — a boundary an employee-facing agent should never cross. A and C invent or grant something the agent has no authority to, and D fails the employee by stopping without explanation or escalation.

**4. D) The model will learn to favour male-associated patterns and carry past bias forward**
This is the Amazon case: a model trained on a skewed history reproduces that skew, even penalising terms like "women's." The other options describe failures that aren't the central, documented risk of biased training data.

**5. B) Grounding the AI by uploading the approved handbook and having it answer from that document**
Grounding ties answers to specific approved sources. Web search (C) does the opposite by pulling in outside information, repetition (A) doesn't anchor anything, and a stronger model (D) still guesses without the right source.

**6. A) Keep findings at the theme level and use anonymised data so no individual can be identified**
Responsible analysis means broad, theme-level summaries on anonymised data. B singles people out, C exposes PII to an unapproved tool, and D misunderstands that engagement data is personal and protected.

**7. C) Job ads = prompt, weekly policy questions = agent, annual analysis = prompt**
The rule is repetition + need for consistency. Unique job ads and a once-a-year analysis are one-off, changing work (prompts); the same weekly policy questions are repetitive and consistency-critical (agent). A and D misapply the logic; B ignores the clear agent use case.

**8. D) Policies changed while the agent's instructions stayed the same (drift); update its instructions first and test edge cases**
Drift is gradual staleness, not a breakage. The fix is to update instructions before employees start asking, and test with realistic edge cases. The other options misdiagnose a maintenance issue as a technical or security failure.

**9. B) Decline to judge readiness and redirect the employee to their manager or HR**
Promotion readiness requires human judgment, context, and accountability — a line a career agent must not cross. A, C, and D all have the agent interpret performance or make a recommendation, which can create false expectations and erode trust.
