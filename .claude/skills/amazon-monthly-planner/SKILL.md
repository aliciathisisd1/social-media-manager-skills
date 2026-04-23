---
name: amazon-monthly-planner
description: Generate structured monthly content ideas for UAE and KSA. Product-first, visually obvious, "i need this" ideas only. Use when the user wants a monthly content outline.
---

# Amazon Monthly Planner

Purpose: generate structured monthly content ideas only. Every idea must be product-first and pass the performance filter. Nothing else.

## Core principle

Every idea must be PRODUCT-FIRST.

The product must either:
- solve a real problem, OR
- create immediate satisfaction or joy.

The viewer must instantly think: **"i need this"**.

## Content style rules

All ideas must follow this format:
1. Start with unboxing OR immediate product reveal.
2. Show the product solving something.
3. Use real environments (desk, kitchen, bathroom, entrance, car).
4. Keep pacing fast and visual.
5. Make the benefit obvious WITHOUT explanation.

## Creative rules

- No talking heads.
- Focus on hands + product interaction.
- Product must be visible within the first 2 seconds.
- No delayed reveal.
- Avoid generic or boring products.
- Avoid products that require explanation.
- Avoid lifestyle fluff.

## Performance filter

Only include ideas that:
- are visually satisfying,
- show transformation (before → after),
- create curiosity or surprise,
- can be understood in under 3 seconds.

## Market rules

- Environments must be culturally appropriate for UAE and KSA.
- Clean backgrounds.
- No inappropriate settings.
- Brand-safe at all times.

## Output

Two tables, one per market. Default 10 UAE ideas, 10 KSA ideas (adjust to requested volume).

| ID | Category | Hook | Product | Problem it solves | Concept (1 line) | Shot Type |

UAE IDs: `AE-001` onward. KSA IDs: `SA-001` onward.

## Rules for the table

- Categories are exactly `Finds` or `Now`.
- Include 4 to 6 Amazon Now per market (scale to volume; for 5-idea batches, include 2 Now).
- Hooks must come from the approved list in `.claude/skills/production-tracker/SKILL.md`. Use exact wording.
- Use varied hooks. No hook repeated within the same market.
- Product column names a specific product type, not a generic category ("magnetic levitating plant pot", not "desk accessory").
- Problem column is one line. Must describe the real-world moment the product solves.
- Concept column is one line. Must be a visual action, not a description.
- Mix shot types: Desk, Kitchen, Bathroom, Outdoor, POV, Close-up, Entrance.

## Amazon Now rules

- Grocery or everyday essentials only.
- Real urgency: problem now, 15-minute fix.
- POV framing. In-the-moment feel.
- Triggers: ran out mid-recipe, last-minute guests, late-night cravings, forgot an essential, kid emergency.

## Rejection rule

If an idea is:
- boring,
- not visually clear, OR
- not instantly useful

DO NOT include it. Replace it.

## Do not include

- Shoot Packs
- Captions
- Production tracker rows
- Preamble or commentary

## Goal

Every idea should feel like: **"why have i never seen this before."**
