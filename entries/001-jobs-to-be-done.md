# Journal Entry 001: Jobs To Be Done — The Theory and the Practice

**Author:** Karani Njoroge
**Date:** June 2026
**Category:** Framework
**Source:** Clayton Christensen — Competing Against Luck + personal application
**Reading Time:** 6 minutes

---

## What I Learned

Jobs To Be Done reframes the fundamental question of product management. Instead of asking "who is my user?" it asks "what is my user trying to accomplish?" The shift sounds subtle but changes everything. When you design for a persona — 34-year-old woman, urban professional — you describe a person. When you design for a job — "help me get medical care without losing a full day of income" — you describe a need that a product can actually solve.

The most important insight: users do not adopt products. They hire them to do a specific job in a specific situation. When a product does that job better than the alternative (including doing nothing), people hire it. When it doesn't, they fire it.

---

## Why It Matters for PMs

JTBD changes how you run research, how you define competitors, and how you measure success. If you know the job, you know who you are competing against — and it is almost never who you think. The hospital queue management platform I am building is not competing against other queue apps. It is competing against the folk wisdom patients use to manage uncertainty (go on Tuesday; bring a friend to hold your place). Understanding that changes what the product needs to do.

---

## Key Concepts

**The Job:** The progress a person is trying to make in a specific circumstance. Always has a functional, emotional, and social dimension.

**The Situation:** The trigger that causes someone to seek a solution. The same person has different jobs in different situations.

**Competing Solutions:** Everything the user currently does instead of your product. The real competitive landscape, not the one defined by industry categories.

**Hiring and Firing:** Users hire a product when it does the job better than alternatives. They fire it when something does it better.

---

## PM Application

When I write user stories, I now start with the situation and motivation, not just the action:

Old format: "As a patient, I want to receive SMS updates on my queue position."
JTBD format: "When I am waiting at a public hospital on a working day, I want to know my position and expected wait so I can preserve my income without risking my place in the queue."

The second version tells me what the feature must accomplish emotionally, not just functionally. It also tells me that the SMS update is only valuable if it is accurate enough to act on — an imprecise update is worse than no update.

---

## Example from My Own Work

Applying JTBD to my hospital queue project revealed a critical insight: the core job is "feel in control of my time during a medical visit," not "wait less." This invalidated my initial solution direction (throughput optimization) and redirected me toward information delivery. The research confirmed it — patients said explicitly: "The problem is not waiting. It is not knowing."

---

## Questions I Still Have

- [ ] How do you handle users who cannot articulate their own job — especially in lower-literacy contexts?
- [ ] How do you validate a JTBD hypothesis without leading the research participant?

---

## Action Items

- [ ] Rewrite all user stories in my hospital queue project using JTBD format
- [ ] Add a "Competing Solutions" section to all future competitor analyses

---

## Related Topics

→ [JTBD Framework Reference](../../pm-frameworks/discovery/jobs-to-be-done.md)
→ [Hospital Queue User Interviews](../../hospital-queue-management/research/user-interviews.md)
