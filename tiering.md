# Vendor Tiering

> [!NOTE]
> Draft. Not yet reviewed.

**Purpose.** Sorting vendors into critical, important, and routine. Everything else in this repo runs off this sort, and the sort takes an afternoon.

## Why Most Vendors Do Not Need Assessing

Assess all 200 vendors equally and you will assess none of them well. The questionnaires pile up, the follow-ups die, and the payroll processor gets the same stale checkbox review as the company that refills the snack wall. Effort follows blast radius or the program collapses under its own fairness.

The honest math: a typical 200-vendor list sorts into roughly 15 critical, 40 important, and everything else routine. Fifteen real assessments a year is a number one person can carry. Two hundred is a number one person can pretend to carry.

## Tier Criteria

**Critical.** Either answer is yes: do they hold regulated or customer data, or does the business stop working without them. Payroll, the cloud platform under your product, the billing system, the identity provider. Note the second half has nothing to do with data, an operational dependency with zero records of yours is still critical, because outage is a risk category too.

**Important.** Some sensitive data but not the crown jewels, or replaceable but painfully. The marketing platform with customer emails, the support desk tool, the accounting add-on.

**Routine.** No sensitive data beyond a billing contact, replaceable in a week without tears. Most of the list, and the tier where the right amount of assessment is nearly none, on purpose, in writing.

## Decision Flow

Three questions per vendor, thirty seconds each. What data of ours do they hold, by classification label. What happens on day three if they vanish. How fast could we replace them. First answer that lands in a tier's definition sets the tier, ties go up. If two people would sort a vendor differently, the criteria need a sentence added, not a meeting.

## Worked Examples

| Vendor | Tier | Why |
|---|---|---|
| Payroll processor | Critical | Regulated employee data, and payday stops without them |
| Cloud hosting under the product | Critical | The business is literally inside it |
| Email marketing platform | Important | Customer emails, hurts to lose, replaceable in a month |
| Support ticketing tool | Important | Customer conversations live there |
| The office snack vendor | Routine | The risk is running out of almonds |
| Free AI tool a team adopted | Depends entirely on data, see the [AI kit](https://github.com/HarrisonWard/ai-governance-kit) | Free is a price, not a tier |

## Reassessment Triggers

A tier is a snapshot of what the vendor touched the day you sorted them. Re-tier on scope creep (the routine tool that now syncs the customer database), on renewal, on their acquisition or breach, and whenever a new integration is requested. The most dangerous vendor on the list is the routine one that became critical one API scope at a time while the file still said "attestation, filed."

---

**Owner:** _name a person_
**Last Reviewed:** not yet
**Review Cycle:** annual
