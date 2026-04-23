---
name: amazon-monthly-planner
description: Generate structured monthly content ideas for UAE and KSA. 10 ideas per market, covering Amazon Finds and Amazon Now. Use when the user wants a monthly content outline.
---

# Amazon Monthly Planner

Purpose: generate structured monthly content ideas only. Nothing else.

## Output

Two tables, one per market. 10 UAE ideas, 10 KSA ideas.

Each row includes only:

| ID | Category | Hook | Concept (1 line) | Shot Type |

UAE table uses IDs: `AE-001` to `AE-010`
KSA table uses IDs: `SA-001` to `SA-010`

## Rules

- Categories are exactly `Finds` or `Now`.
- Include 4 to 6 Amazon Now per market. The rest are Amazon Finds.
- Hooks must come from the approved list in `.claude/skills/production-tracker/SKILL.md`. Use exact wording.
- Use varied hooks. No hook repeated within the same market.
- UAE concepts feel locally relevant: heat, apartments, Marina, Dubai commute, rooftop life.
- KSA concepts feel locally relevant: family gatherings, majlis, gahwa, dates, home setups.
- Mix shot types: Desk, Kitchen, Bathroom, Outdoor, POV, Close-up.

## Amazon Now rules

- Focus on grocery or everyday essentials.
- Show urgency: problem, then 15-minute solution.
- Feel in-the-moment. Good triggers: ran out mid-recipe, last-minute guests, late-night cravings, forgot an essential.

## Do not include

- Shoot Packs
- Captions
- Production tracker rows
- Long explanations or commentary
