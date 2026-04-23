---
name: amazon-monthly-planner
description: Plan a month of Amazon content by volume and market, returning hook, concept, shot type, and category per item. Use when the user wants a bulk content outline across UAE and KSA.
---

# Amazon Monthly Planner

Lightweight planning skill. Turn a volume target into a clean content table. No Shoot Packs, no captions, no tracker rows.

## Inputs

- Total videos per market (e.g. 10 UAE, 10 KSA).
- Amazon Now quota per market (default 4 to 6).

## Output

One table, these columns only:

| ID | Market | Category | Hook | Concept (1 line) | Shot Type |

## Rules

- IDs use market prefix: `AE-001` for UAE, `SA-001` for KSA.
- Categories are exactly `Finds` or `Now`.
- Hooks must come from the approved list in `.claude/skills/production-tracker/SKILL.md`. Use exact wording.
- Each hook appears at most once per market for variety. Only repeat when volume per market exceeds 10.
- UAE content feels locally relevant: heat, apartments, Marina, Dubai commute, rooftop life.
- KSA content feels locally relevant: family gatherings, majlis, gahwa, dates, home setups.
- Mix shot types across the batch: Desk, Kitchen, Bathroom, Outdoor, POV, Close-up.

## Amazon Now rules

- Focus on grocery or everyday essentials.
- Show real urgency (problem, then 15-minute solution).
- Feel in-the-moment. POV-friendly, not studio.
- Good triggers: ran out mid-recipe, last-minute guests, late-night cravings, forgot an essential.

## Keep it tight

One table, no commentary, no long explanations.
