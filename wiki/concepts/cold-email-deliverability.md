---
tags: [cold-email, outbound-sales, sales-tech-stack]
sources: [x-23m-cold-emails-lessons.md, linkedin-cold-outreach-process.md]
created: 2026-04-10
updated: 2026-04-10
---

# Cold Email Deliverability

The infrastructure required to land cold emails in the primary inbox rather than spam. [[ColdIQ]] achieved 57.59% reply rates by prioritizing deliverability over volume.

## Core Rules

- **Authentication:** SPF, DKIM, DMARC on every sending domain
- **Secondary domains:** Never send from your primary domain. Use dedicated outreach domains.
- **Warming:** Start at 5 emails/day, add 5 more daily. Maintain 40%+ reply rates during warm-up. Warm for 2+ weeks before campaigns.
- **Volume limits:** 20-50 emails per domain per day maximum
- **No open tracking:** Tracking pixels hurt deliverability
- **Domain rotation:** Replace underperforming domains every 9-12 months
- **List hygiene:** Verify every email address before sending (DeBounce, [[Prospeo]])

## Key Insight

From 23M+ cold emails: micro-lists of 500-1,000 contacts outperform blasts of 10,000+. One enriched signal is worth 100 raw emails. A 4-step sequence outperforms a 7-step sequence when targeting is right.

Deliverability is the foundation that makes [[Tiered Prospecting]], [[Signal-Based Outbound]], and [[Allbound]] possible. Without it, nothing else matters.
