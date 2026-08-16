# Risk Acceptance

> [!NOTE]
> Draft. Not yet reviewed.

**Purpose.** When a critical vendor fails and you need them anyway. **51% of a Security Program Is Acknowledging the Risk**, applied to the vendor list.

## This Is Normal

Run a real program for a year and you will find a critical vendor with genuine problems that the business cannot or will not replace. The niche platform the whole industry runs on. The processor mid-migration. The tool with three years left on the contract and no MFA story. This is not a program failure, it is the program working: the alternative was not a safer vendor, it was the same vendor with nobody looking.

## Who Accepts the Risk

The business owner of the relationship. Not you, not the security function, not a committee diffusing it into fog. The person who chose the vendor and benefits from it signs for what it could cost, because risk acceptance by someone with nothing at stake is theater with a signature line. Your job is making sure they understand what they are signing, in plain sentences, and that saying no to the acceptance stays a real option all the way to the pen.

## What Must Be Documented

One page: the vendor, the gap in plain English, what could plausibly go wrong and roughly how badly, what we asked them to fix and their answer, the compensating controls below, the expiry date, and the owner's signature. The [starter repo's exception form](https://github.com/HarrisonWard/Security-Program-Starter/blob/main/templates/exception-request.md) is the shape; this is that form pointed at a vendor. If the write-up takes more than a page, the gap is not understood yet, and signing an ununderstood risk is the one move this process exists to prevent.

## Compensating Controls

Named, real, and honest about their size. Less data shared with the vendor, tighter access on your side of the integration, exports disabled, alerts on their traffic, a tested exit plan, contractual teeth added at the next renewal. "We will monitor closely" is not a control, it is a mood. And where the honest answer is that no meaningful compensation exists, the form says so, because a signed acceptance of a naked risk is at least true, and true is what the process sells.

## Review Cadence

Every acceptance expires, 90 days to one year by severity, and expiry means re-decided, not auto-renewed. The re-decision asks what changed: did the vendor fix anything, did our exposure grow, did an alternative appear. Renewal of the acceptance takes the same signature it took the first time, which is the design: mild friction, applied to the person with the power to demand better, at exactly the interval where demanding better might work.

## Making It Not Theater

Three tells separate a real acceptance process from a rubber stamp. The register of open acceptances is short, because a long one means the tiering or the scoring is broken upstream. Somebody has actually declined to sign one at least once, because a process nobody has ever said no through is a formality. And the acceptances feed the renewal calendar, so the leverage moment and the expiry date collide on purpose. Do those three and the executive who signs learns the thing this whole repo exists to teach: the risk was always theirs, the paperwork just stopped pretending otherwise.

---

**Owner:** _name a person_
**Last Reviewed:** not yet
**Review Cycle:** quarterly, it is the register that keeps the rest honest
