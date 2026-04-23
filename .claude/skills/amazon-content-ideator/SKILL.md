---
name: amazon-content-ideator
description: Turn sourced Amazon products into product-first content ideas. Second step in the Amazon content workflow. Requires sourced products as input.
---

# Amazon Content Ideator

Purpose: turn sourced products into content ideas. Second step. Cannot run without sourced products.

## Input

A list of sourced products from `amazon-product-sourcing`. Each must include product name, category, and visual potential.

## Core principle

Every idea must be PRODUCT-FIRST.

The viewer must instantly think: **"i need this"**.

## Mandatory video structure

Every idea must map to:
1. Hook (0–2 sec) — grab attention.
2. Reveal (2–3 sec) — product visible immediately.
3. Context (2–5 sec) — show the problem.
4. Product in action (5–15 sec).
5. Result — clear visible outcome.

## Output

| ID | Category | Hook | Product | Problem | Concept (1 line) | Shot Type |

ID matches the sourced product ID (AE-001 → idea AE-001).

## Rules

- Hooks must come from the approved list in `production-tracker/SKILL.md`. Use exact wording.
- No hook repeated within the same market.
- Concept describes a visual action, not a description.
- Mix shot types: Desk, Kitchen, Bathroom, POV, Close-up, Entrance, Outdoor.
- Include 4 to 6 Amazon Now per market when volume allows.

## Performance filter

Reject any idea that:
- is not visually clear,
- does not show transformation,
- cannot be understood in under 3 seconds,
- does not trigger "i need this".

## Do not include

- Production briefs
- Edit instructions
- Captions
- Preamble or commentary

## Hand-off

Approved ideas feed `amazon-production-planner`.
