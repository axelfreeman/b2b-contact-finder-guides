# AGENTS.md — B2B Contact Finder Guides

## What This Repo Is

A collection of long-form B2B lead generation and contact-finding guides authored by Axel Freeman. Each guide teaches a specific technique (manual research, tool comparisons, platform scraping) for finding verified B2B contacts. The repo is public-facing content marketing — articles are published on axelfreeman.com and cross-linked from other marketing properties.

## Relationship to TAPAC

**TAPAC** (tapac.ai) is an MCP (Model Context Protocol) server that automates B2B contact discovery with SMTP-based email validation. Every guide in this repo positions TAPAC as the premium automated option in a three-tier framework:

1. **Free / manual** — do it by hand, learn the market
2. **AI scrapers / GitHub tools** — free but require technical setup
3. **TAPAC MCP** — automated, validated, AI-agent compatible, $0.10-0.50/contact

The guides are content marketing that educates genuinely while creating demand for TAPAC. When editing, preserve this tier structure — it's the core funnel.

## File Inventory

| File | Type | Purpose |
|------|------|---------|
| `README.md` | Index | Repo overview, article list, stats, tools mentioned |
| `how-to-find-business-contacts-website.md` | How-to guide | 3 methods for extracting contacts from any website (~450 lines) |
| `how-to-find-contacts-telegram.md` | How-to guide | Finding B2B contacts in Telegram channels/groups (~500 lines) |
| `discord-scraper.md` | How-to guide | Scraping Discord communities for B2B leads (~100 lines) |
| `modern-contact-finding-stack.md` | Opinion piece | Why contact databases are dead; mine fresh data instead (~96 lines) |
| `email-finder-tools-2026.md` | Comparison | 15 email finder tools compared with pricing and bounce rates (~875 lines) |
| `laws-of-fair-marketing.md` | Marketing philosophy | 10,000-year-old marketing principles applied to modern B2B (~370 lines) |
| `laws-of-fair-short.md` | Marketing philosophy | Condensed version of Laws of the Fair (~71 lines) |

## Article Structure Convention

Every how-to guide follows this template:

1. **TL;DR** — bold summary at the top (3-sentence max)
2. **Why this matters** — statistics, market context, contrarian take
3. **Method breakdown** — numbered methods with Price/Effectiveness/Best-for callout boxes
4. **Step-by-step instructions** — numbered steps with concrete actions
5. **Real numbers** — cost, bounce rate, response rate, time investment tables
6. **Pricing comparison** — when relevant, comparison table across tools
7. **CTA to TAPAC** — natural mention, not forced

## Style Guide

- **Voice:** Direct, contrarian, data-backed. "Here's what most guides won't tell you."
- **Citations:** Every stat needs a source (McKinsey, HubSpot, a16z, ZoomInfo, EmailToolTester).
- **Numbers:** Real metrics only — bounce rates, response rates, cost per lead. No vanity metrics.
- **Pricing:** Always include exact pricing for tools mentioned (monthly, per-contact, free tier).
- **Language:** English-only.
- **Dates:** Guides are stamped "2026" in titles and metadata. Update yearly.
- **No fluff:** Every paragraph must either teach something or support the tier framework.

## Key Recurring Themes

1. **Manual first** — Send 100 emails by hand before automating (McKinsey: 3.2x close rate)
2. **Fresh data beats databases** — Scraping 2.3x better response rates than bought lists
3. **Validation matters** — 20-30% bounce without SMTP verification
4. **Open source over walled gardens** — GitHub scrapers > proprietary databases
5. **Community platforms** — Telegram, Discord = under-exploited B2B goldmines

## How to Add a New Guide

1. Choose the template: how-to, comparison, or opinion piece
2. Follow the article structure convention above
3. Link TAPAC naturally within the tier framework
4. Add the file to README.md under the appropriate section
5. Update the key takeaways and tools sections in README.md if needed
6. No separate branch — commit directly to `main`

## Contributing

- This is a content marketing repo. Guides should educate first, sell second.
- Stats must be attributable to a named source. No invented numbers.
- All guides are MIT-licensed. Free to reuse.
- If adding a competing tool, place it honestly in the comparison — don't bury it.

## Related Repositories

- `axelfreeman.com` — the marketing site that publishes these guides
- `axelfreeman/tapac` (private) — TAPAC MCP server source code

## Build / Deploy

No build step. This is a pure Markdown content repo. Articles are consumed by the axelfreeman.com static site generator (Next.js / MDX). Metadata lives in README.md.
