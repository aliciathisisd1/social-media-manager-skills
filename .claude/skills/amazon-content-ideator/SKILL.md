---
name: amazon-content-ideator
description: Turn approved sourced products into strong content ideas. Second step in the Amazon content workflow. Requires sourced products as input.
---

# Amazon Content Ideator

Purpose: turn approved sourced products into strong content ideas. Second step. Cannot run without sourced products.

## Input

A list of approved products from `amazon-product-sourcing`.

## Rules

- Must use approved hooks only (from `production-tracker/SKILL.md`).
- Product must appear in the first 2 seconds.
- Must feel product-centric.
- Must show problem to solution clearly.
- No talking heads.
- Hands and product interaction preferred.
- Must feel personal, relatable, and honest.
- Avoid ad-like language.
- Avoid forced messaging.
- Avoid over-explaining.

## Mandatory video structure

Every idea must map to this exact structure:

1. **Hook (0–2 sec)** — grab attention immediately.
2. **Unboxing or product reveal (2–3 sec)** — product visible right away.
3. **Context / problem (2–5 sec)** — show the situation.
4. **Product in action (5–15 sec)** — show usage.
5. **Result / outcome** — clear visible payoff.

## Output

One entry per idea:

**Hook:** (exact wording from approved list)
**Product:** (specific item name)
**Problem it solves:** (1 line)
**Concept:** (1 line — a visual action, not a description)
**Shot type:** (Desk / Kitchen / Bathroom / POV / Close-up / Entrance / Outdoor)
**Category:** (Amazon Finds or Amazon Now)

## Rejection rule

Do not include any idea that:
- cannot be understood in under 3 seconds,
- does not show clear transformation,
- feels generic or ad-like.

## Do not include

- Production briefs
- Edit instructions
- Captions
- Preamble or commentary

## Hand-off

Approved ideas feed `amazon-production-planner`.
