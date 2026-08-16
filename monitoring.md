# Continuous Monitoring

> [!NOTE]
> Draft. Not yet reviewed.

**Purpose.** Ongoing monitoring on a budget of roughly zero. The ratings platforms are fine if you have the money. This page assumes you do not, and that an hour a month spent well beats a dashboard nobody opens.

## What Is Worth Monitoring

Only the critical tier, and only for changes that would change your decision: they got breached, they got acquired, their terms or subprocessors changed, their product quietly grew AI features, or their service reliability fell off a cliff. You are not monitoring their security posture in real time, nobody outside their walls can, you are watching for the events that reopen the file.

## Free and Low-cost Sources

News alerts on each critical vendor's name plus the word breach, five minutes to set up, runs forever. Their status page and incident history, subscribed, because chronic small outages predict the big one. Their trust or security page, checked at renewal for silent edits. The SOC 2 renewal calendar: reports expire annually, and a vendor whose report quietly goes stale is telling you something. Breach notification laws doing your work: half the time you learn from the disclosure letter, so make sure the register knows where those letters arrive. And the best sensor money cannot buy: the business owner who uses the tool daily and notices weirdness a quarter before any feed does, if you have asked them to tell you.

## Cadence

Monthly, thirty minutes, calendar-held: sweep the alerts, glance at status pages, check nothing on the critical list hit the news. Quarterly, add the register hygiene pass: renewals coming due, reports expiring, re-assessments owed. That is the whole program, and its durability is the feature; the elaborate version gets skipped in month three.

## What to Do with a Finding

A finding reopens the file, it does not start a panic. Breach in the news: send the three questions (were we affected, what data, what changed), clock their answer against the contract's notification promise, and note the gap between the two, which is diligence gold. Acquisition: re-run tiering at next renewal, ownership changes change risk appetite. Feature or terms creep: re-tier now, the [triggers page](tiering.md) owns this. And every finding, even the nothingburgers, gets one line in the register, because the pattern across findings is the actual monitoring product.

---

**Owner:** _name a person_
**Last Reviewed:** not yet
**Review Cycle:** annual
