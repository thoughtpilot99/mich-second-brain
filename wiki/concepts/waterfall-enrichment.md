---
tags: [data-enrichment, outbound-sales, gtm-engineering, sales-tech-stack]
sources: [x-one-clay-table-all-clients.md, profile-michel-lieben.md]
created: 2026-04-10
updated: 2026-04-10
---

# Waterfall Enrichment

Using multiple data providers in sequence (waterfall) to maximize coverage and minimize cost. [[Clay]] aggregates 75+ providers; if the first provider doesn't have the data, it falls to the next.

## The API Hack

[[Michel Lieben]] documented a technique using [[Clay]]'s API directly instead of the UI credit model. Costs drop from $0.15-$0.30 to $0.03-$0.08 per lead -- a 70-80% savings. Essential for high-volume outbound at [[ColdIQ]]'s scale.

## One Table for All Clients

[[ColdIQ]] runs a single [[Clay]] table across every client. Five automated stages: blocklist ingestion, lead sourcing, enrichment, scoring, and routing. This architecture 3X's TAM while saving credits.

Waterfall enrichment feeds into [[Tiered Prospecting]] and [[Signal-Based Outbound]], providing the clean data foundation that makes targeted outreach possible.
