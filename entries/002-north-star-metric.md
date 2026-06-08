# Journal Entry 002: North Star Metric — Why One Number Changes Everything

**Author:** Karani Njoroge
**Date:** June 2026
**Category:** Metrics
**Source:** Amplitude — North Star Playbook + personal application
**Reading Time:** 5 minutes

---

## What I Learned

A North Star Metric is a single number that best represents the core value your product delivers to users. It is not a business metric (revenue, sign-ups) — it is a user value metric that, when it grows, indicates the product is genuinely working. The thesis is that teams aligned around one meaningful metric make better decisions, faster, with less internal conflict.

The key criterion for a good north star: it must capture value delivered to users, not value captured by the business. DAU (daily active users) measures engagement. "Patients served per day who registered via SMS" measures value. Only the second one can actually tell you if the product is working.

---

## Why It Matters for PMs

Without a north star, different people on the same team optimize for different things. Engineering ships features. Marketing reports sign-ups. Support tracks tickets. None of these tells you whether the product is creating value. A north star forces a single answer to the question "is this working?" and aligns every decision around it.

---

## Key Concepts

**North Star:** One metric that captures the value the product delivers to users at scale.

**Input Metrics:** The 3–5 metrics that the team can directly influence, which together drive the north star.

**Vanity Metrics:** Metrics that look good but do not indicate real value (page views, downloads, registered users with no activation).

---

## Example from My Own Work

For my hospital queue platform, I chose: **Patients served per day who registered via SMS.**

Alternatives I rejected:
- "SMS registrations per day" — measures activity, not completion. A patient who registers but abandons has not been helped.
- "Abandonment rate reduction" — a lagging indicator. It tells me what happened, not what the product drove.
- "Staff dashboard daily active users" — measures staff adoption, not patient value.

My north star captures both product adoption (SMS registration) AND clinical value (being served) in one number. It only goes up when the product is genuinely working.

---

## Questions I Still Have

- [ ] How do you choose between two plausible north star metrics when you are pre-launch and have no data?
- [ ] How often should a north star metric change as the product matures?

---

## Action Items

- [ ] Add explicit north star sections to all project metrics documents
- [ ] Apply this framework to one product teardown — evaluate whether the product has an implicit north star

---

## Related Topics

→ [North Star Metric Framework](../../pm-frameworks/metrics/north-star.md)
→ [Hospital Queue Metrics](../../hospital-queue-management/launch/metrics.md)
