# Comms 101 Guide for Support Team

_Effective Communication for Technical Incidents_

---

## 1. Purpose

This guide empowers support teams to communicate clearly, empathetically, and professionally during incidents. Learn to:

- Simplify technical jargon for non-technical audiences.
- Balance transparency with reassurance.
- Use templates as frameworks (not copy-paste).
- Escalate and approve messages efficiently.

---

## 2. Core Principles

| Principle        | Description                                                              | Example                                                                                                                                       |
| ---------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Conciseness**  | Avoid fluff. Focus on **what happened**, **impact**, and **resolution**. | ❌ _"We’re investigating a multifaceted system anomaly."_<br>✅ _"We’re aware of delays and are working to resolve them."_                    |
| **Transparency** | Be honest without oversharing. Avoid blame.                              | ❌ _"Our engineers messed up the code."_<br>✅ _"A system error caused temporary delays."_                                                    |
| **Empathy**      | Acknowledge frustration.                                                 | ❌ _"This issue is under investigation."_<br>✅ _"We know this disrupted your workflow, and we’re sorry."_                                    |
| **Clarity**      | Use plain language.                                                      | ❌ _"IPFS retry logic induced a thundering herd problem."_<br>✅ _"A system error caused repeated failed requests, overloading our servers."_ |

---

## 3. Writing Guidelines

### Do

- Start with empathy (e.g., _“We apologize for the inconvenience”_).
- Use active voice (e.g., _“We fixed the issue”_ vs. _“The issue was fixed”_).
- Specify **who is affected**, **what’s happening**, and **timeline** (if known).

### Don’t

- Use jargon (e.g., _“root cause,” “post-mortem”_).
- Overpromise (e.g., _“This will never happen again”_).
- Share unverified details.

---

## 4. Examples of Good vs. Bad Messaging

### Scenario 1: Incident Acknowledgment

❌ _“We’re investigating elevated error rates.”_  
✅ _“We’re aware of delays affecting some users and are working to resolve this ASAP. We’ll share updates by 5 PM ET.”_

**Why it works:** Specifies impact, timeline, and empathy.

### Scenario 2: Progress Update

❌ _“The team identified a missing patch in the retry logic.”_  
✅ _“We found a system error causing repeated failed requests and have applied a fix. Services are recovering, and we’ll monitor closely.”_

**Why it works:** Translates technical details into plain language.

### Scenario 3: Post-Mortem Summary

❌ Full technical post-mortem copy-pasted.  
✅ _“On [DATE], a system error caused delays for some users. We fixed the issue within 2 hours and are improving our testing process to prevent recurrence.”_

**Why it works:** Condenses key details (cause, resolution, prevention).

---

## 5. Using Templates Effectively

Templates are **frameworks**, not final copy. Customize for context:

### Template for Incident Acknowledgment

Hi [Customer],

We’re aware of [issue description] impacting [specific service/users]. Our team is actively investigating and will share updates ASAP. We apologize for the inconvenience and appreciate your patience.

— The Graph Support Team

**Customization Tips:**

- Add impacted service names (e.g., _“subgraph queries”_).
- Adjust timelines based on severity.

---

## 6. Approval Workflow & Escalation

- **Tier 1 Customers**: Always get Tech Writer/BK approval.
- **Other Customers**: Use the checklist below. If unsure, tag `@tech-writer` in Slack.
- **Escalation**: No response in 1 hour? Ping again. No reply in 2 hours? Page the on-call manager.

---

## 7. Comms 101 Checklist

Before sending **any** message, ask:

- [ ] **Empathy**: Does it start with an apology or acknowledgment?
- [ ] **Clarity**: Would a non-technical user understand this?
- [ ] **Transparency**: Does it explain the issue without blame?
- [ ] **Action**: Does it specify next steps or timelines?
- [ ] **Approval**: Does it require escalation? (Use Tier 1/2 guidelines.)

---

## 8. Maintaining Brand Voice

- **Tone**: Professional yet approachable. Avoid robotic language.
- **Branding**: Use approved templates in Notion/Slack.
- **Consistency**: Ensure all summaries align with The Graph’s style guide.

---

## 9. Practice Exercise

Rewrite this message using the checklist:  
❌ _“We had a database outage due to a node failure. Engineers are fixing it.”_

✅ _“We’re aware of a system issue causing delays and are working to resolve it. We’ll share an update within 30 minutes. Thank you for your patience!”_

---

## 10. Linked Resources

- [Post-Mortem Summary Template](#)
- [Incident Playbook](#)
- [Brand Voice Guidelines](#)

---
