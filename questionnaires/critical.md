# Critical Vendor Questionnaire

> [!NOTE]
> Draft. Not yet reviewed.

**Purpose.** About 30 questions. The ones that change a decision. Every question here earns its place by having an answer that could alter the tier, the contract, or the approval, and anything that could not has been deleted. Send it with a deadline, a named contact, and the [chasing plan](../chasing.md) ready.

## Governance

1. Who owns security at your company, by name and title, and who do they report to?
2. Which framework do you align to, and what third-party attestation or certification do you hold against it, current copy requested below?
3. When did your last penetration test happen, who performed it, and were the critical findings fixed?
4. Have you had a security incident affecting customer data in the last three years? What happened, and what changed after?
5. How many people at your company can access our data, and what determines who can?

## Access Control

6. Is MFA enforced for all staff access to systems holding customer data, with no exceptions? If exceptions exist, list them.
7. Is MFA enforced on your own cloud and infrastructure admin accounts? (Only 23% of third parties fully fix this when told, per the 2026 DBIR, which is exactly why it is asked directly.)
8. How is access removed when your employees leave, and how fast?
9. Do your staff use unique named accounts, or do shared accounts exist anywhere in the path to our data?
10. Is customer data accessible from personal or unmanaged devices?

## Data Handling

11. Where is our data stored and processed, by country and provider?
12. Is our data encrypted in transit and at rest, and who holds the keys?
13. Is our data logically separated from other customers', and how?
14. Do you use our data for anything beyond delivering the service, including analytics, product improvement, or AI training?
15. Who at your company can export our data in bulk, and is that logged?
16. When we leave, how is our data returned and destroyed, and what proof do we get?

## Resilience

17. What is your availability commitment, and what did your worst outage last year look like?
18. What are your backup arrangements, and when did you last restore from them, actually restore, not intend to?
19. Do you have a tested business continuity plan, and when was the last exercise?
20. What single points of failure exist in delivering our service, including your own key vendors?

## Incident Response

21. Do you have a documented incident response plan with a named owner?
22. How fast will you notify us of an incident affecting our data, and is that number in our contract or just in this answer?
23. Who specifically calls whom? Give us a name and a channel, not a mailbox.
24. Have you tested your response in the last year, tabletop or real?

## Subprocessors

25. List the subprocessors that touch our data, and where they are.
26. How do you assess them? You are our vendor risk; who does yours?
27. Will you notify us before adding or changing a subprocessor that touches our data?
28. Does any AI feature in your product send our data to a model provider, and can we turn it off?

## Evidence Requested

29. Current SOC 2 Type II or ISO 27001 certificate, read past the logo per [the bathroom problem](https://github.com/HarrisonWard/Security-Program-Starter/blob/main/mappings/soc2.md): system boundary, criteria, exceptions, carve-outs.
30. Proof of cyber insurance, penetration test summary letter, and the incident notification commitment in writing.

The scoring of what comes back lives in [scoring.md](../scoring.md), and the two or three answers worth a phone call are usually 4, 14, and 22. The value is in the follow-up, not the form.

---

**Owner:** _name a person_
**Last Reviewed:** not yet
**Review Cycle:** annual
