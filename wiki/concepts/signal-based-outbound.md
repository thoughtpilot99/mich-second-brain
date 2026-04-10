---
tags: [outbound-sales, b2b-lead-generation, gtm-engineering]
sources: [x-18-buying-signals.md, linkedin-cold-outreach-process.md, x-cold-outreach-25k-leads.md]
created: 2026-04-10
updated: 2026-04-10
---

# Signal-Based Outbound

Targeting prospects based on buying signals rather than broad demographic lists. Core philosophy: "Email people who already want to buy."

## 18 Buying Signals

**First-Party** (your ecosystem): LinkedIn profile views, website visits, content engagement, email opens/clicks, webinar attendance, trial signups.

**Third-Party** (external data): Job postings, funding events, tech stack changes, competitor engagement, industry event attendance, company growth signals.

**Intent** (research behavior): G2/Capterra reviews, category keyword searches, content downloads, social discussions, community participation, analyst report downloads.

## Implementation

[[ColdIQ]] uses [[Clay]] and [[Common Room]] to detect signals, then routes to [[Tiered Prospecting]] for prioritization. The [[GTM Engineer]] builds automated signal-detection workflows using [[Claude Code]] and [[n8n]].

This approach is central to [[Allbound]] -- all three channels (content, ads, outbound) generate signals that feed back into targeting.
