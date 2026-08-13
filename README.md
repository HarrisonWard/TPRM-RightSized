# TPRM Right-Sized

Third-party risk management that a mid-market company can actually run. Vendor tiering, questionnaires that fit on two pages, a scoring model, contract language, and the part nobody writes about — how to get vendors to respond at all.

Most published TPRM material is either a vendor pitch or built for a 10,000-person enterprise with a dedicated team. If you have 300 employees, 200 vendors, and one person doing this part-time alongside three other jobs, none of it is usable.

---

## Who this is for

- Security and IT leaders at mid-market companies who own vendor risk among other things
- Compliance teams answering "do you assess your vendors" for the first time
- vCISOs standing up a program for a client who has nothing
- Anyone who has been handed a 300-question SIG and quietly given up

## Who this is not for

- Large enterprises with dedicated TPRM teams and a GRC platform. You need more than this.
- Anyone looking for a tool or continuous monitoring service. This is process and documents.

---

## What's inside

| File | What it is |
|---|---|
| `tiering.md` | Criteria for sorting vendors into critical, important, and routine |
| `questionnaires/critical.md` | ~30 questions. The ones that actually change a decision. |
| `questionnaires/important.md` | ~15 questions |
| `questionnaires/routine.md` | 5 questions and a request for their SOC 2 |
| `scoring.md` | How to turn answers into a rating without pretending it's precise |
| `risk-acceptance.md` | What happens when a vendor fails and you need them anyway |
| `contracts/security-clauses.md` | Contract language covering breach notification, subprocessors, audit rights, data return |
| `monitoring.md` | Continuous monitoring on a budget of roughly zero |
| `chasing.md` | Getting responses out of vendors who ignore you |
| `onboarding-checklist.md` | The end-to-end flow from request to approved |

---

## The core idea

**Most vendors do not need assessing.**

That sentence is heresy in TPRM circles and it is also true. If you assess every vendor equally, you will assess none of them well. The office snack supplier and the payroll processor do not carry the same risk, and treating them the same is how programs collapse.

| Tier | What qualifies | Assessment | Reassess |
|---|---|---|---|
| **Critical** | Holds regulated or customer data, or the business stops without them | Full questionnaire + evidence + call | Annually |
| **Important** | Some sensitive data, or meaningful operational disruption if lost | Short questionnaire + SOC 2 review | Every 2 years |
| **Routine** | No sensitive data, easily replaced | Attestation, filed | On renewal |

If you do this well, you might have 15 critical vendors out of 200. Fifteen is a number one person can actually handle.

---

## Why the questionnaire is 30 questions, not 300

A 300-question assessment produces one of two outcomes. Either the vendor ignores it, or someone in their sales org fills it out in an afternoon with answers optimized for getting past you.

Neither tells you anything.

Thirty questions, answered carefully, with two or three followed up by a real conversation, will tell you more about a vendor's security posture than any questionnaire ever written. The value is in the follow-up, not the form.

The critical questionnaire here is built around the questions where a bad answer actually changes your decision. Everything else was cut.

---

## The part nobody writes about

`chasing.md` covers the unglamorous reality: you sent the questionnaire, and nothing came back.

- Who to send it to (hint: not your account rep)
- Timing it against contract renewal, which is the only leverage you have
- What to do when a vendor flatly refuses
- When to escalate to your own business owner instead of the vendor
- When to accept the risk, document it, and move on

This is where most programs actually fail. Not in the framework. In the follow-up email nobody sends.

---

## On risk acceptance

You will find a critical vendor with real gaps that the business cannot replace. This is normal and it is not a failure.

The job is not to eliminate the risk. The job is to make sure the person who owns the business relationship knows what they are accepting, says so in writing, and revisits it. `risk-acceptance.md` covers doing that without turning it into theater.

---

## What this is not

Not legal advice. Contract language here is a starting point for discussion with your counsel, not something to paste into an agreement. Regulatory requirements for third-party oversight vary significantly by sector — financial services, healthcare, and critical infrastructure all carry specific obligations this does not address.

Nothing here is drawn from any client engagement.

---

## Contributing

Interested in: sector-specific question sets, contract language that survived actual negotiation, and monitoring approaches that work without a budget.

Nothing client-identifiable. No vendor promotion.

---

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use it, adapt it, use it commercially. Just give credit.

© 2026 Harrison Ward

---

## About

Cyber risk and technology executive. Built third-party and supply-chain risk programs for enterprise clients as SVP in Kroll's Cyber Risk practice, and established vendor risk practices as CTO of a multi-office professional services firm.

More at [github.com/HarrisonWard](https://github.com/HarrisonWard) · [LinkedIn](https://linkedin.com/in/harrisonaward)
