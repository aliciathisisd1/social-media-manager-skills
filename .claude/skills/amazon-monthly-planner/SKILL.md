---
name: amazon-monthly-planner
description: Generate structured monthly content ideas for UAE and KSA. Product-first, visually obvious, "i need this" ideas only, aligned to season, culture, and top-performing categories. Use when the user wants a monthly content outline.
---

# Amazon Monthly Planner

Purpose: generate structured monthly content ideas only. Every idea must be product-first, pass the performance filter, and fit the time of year and market. Nothing else.

## Core principle

Every idea must be PRODUCT-FIRST.

The product must either:
- solve a real problem, OR
- create immediate satisfaction or joy.

The viewer must instantly think: **"i need this"**.

## Seasonal + cultural planning (CRITICAL)

Content must reflect the time of year, cultural moments, and local relevance.

When planning, always consider:
- Month
- Cultural events
- Weather conditions
- Travel patterns
- Social behaviour in UAE and KSA

### Key moments to incorporate

- **Ramadan** — cooking, hosting, convenience. Time-saving kitchen tools. Amazon Now grocery moments.
- **Eid Al Adha** — travel, packing, organisation. Quick prep, gifting.
- **UAE National Day** — travel, outdoor, road trips. Convenience products.
- **Saudi National Day** — celebration items. Home setups, decor.
- **World Cup / major sports** — snacks (Amazon Now). Football-related items. Social viewing setups.

### Weather insight

- **Summer (extreme heat)** — cooling solutions, indoor comfort, convenience products. Avoid outdoor-heavy content.
- **Winter (Nov–Feb)** — camping, outdoor setups, travel gear.

### Market performance priority

When selecting products, prioritise high-performing categories per market.

**UAE (in order):**
1. Grocery (Amazon Now)
2. Kitchen & Dining
3. Appliances
4. Sports
5. Electronics
6. Beauty & Personal Care

**KSA (in order):**
1. Home & Garden
2. Toys & Games
3. Home-related products
4. Electronics
5. Appliances
6. Kitchen & Dining

### Distribution rule

Across the planned batch:
- Majority of products must come from the top-performing categories above.
- Still include some variety for freshness.
- Do not over-index on low-performing categories.

## Video structure (mandatory)

Every idea must follow this exact structure:

1. **Hook (0–2 sec)** — grab attention.
2. **Unboxing / product reveal (2–3 sec)** — product visible immediately.
3. **Context (2–5 sec)** — show the situation or problem.
4. **Product in action (5–15 sec)** — show usage.
5. **Result** — clear, visible outcome.

## Content style rules

- Start with unboxing OR immediate product reveal.
- Show the product solving something.
- Film in real environments (desk, kitchen, bathroom, entrance, car).
- Keep pacing fast and visual.
- Make the benefit obvious WITHOUT explanation.

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

## Do not include

- Ad-like or scripted content.
- Showing product without using it.
- Slow starts.
- Overcomplicated ideas.
- Over-editing or over-production.
- Web links, URLs, or external CTAs.
- Products not sold on Amazon.
- Negative or comparative reviews.
- Content aimed at children.
- Health or medical claims.
- Weight loss claims.
- Medical advice.
- Alcohol-related products (any form).

## Tone and style

Aim for: personal, relatable, honest.

Avoid: sales language, forced messaging, over-explaining.

## Market rules

- Environments must be culturally appropriate for UAE and KSA.
- Clean backgrounds.
- Brand-safe at all times.

## Output

Two tables, one per market. Default 10 UAE ideas, 10 KSA ideas (adjust to requested volume).

| ID | Market | Category | Hook | Product | Problem it solves | Concept (1 line) | Shot Type | Why this fits the current moment (1 line) |

UAE IDs: `AE-001` onward. KSA IDs: `SA-001` onward.

## Table rules

- Categories are exactly `Finds` or `Now`.
- Include 4 to 6 Amazon Now per market (scale to volume; for 5-idea batches, include 2 Now).
- Hooks must come from the approved list in `.claude/skills/production-tracker/SKILL.md`. Use exact wording.
- Use varied hooks. No hook repeated within the same market.
- Product column names a specific product type, not a generic category.
- Problem column is one line. Must describe the real-world moment the product solves.
- Concept column is one line. Must describe a visual action, not a general description.
- "Why this fits the current moment" column must reference season, cultural event, weather, or market priority. One line. Not filler.
- Mix shot types: Desk, Kitchen, Bathroom, Outdoor, POV, Close-up, Entrance.

## Amazon Now rules

- Grocery or everyday essentials only.
- Real urgency: problem now, 15-minute fix.
- POV framing. In-the-moment feel.
- Triggers: ran out mid-recipe, last-minute guests, late-night cravings, forgot an essential, kid emergency.

## Rejection rule

If an idea:
- feels generic,
- is not visually clear,
- does not create an "i need this" reaction, OR
- does not fit the current season, cultural moment, or top-performing category

DO NOT include it. Replace it.

## Do not include in output

- Shoot Packs
- Captions
- Production tracker rows
- Preamble or commentary

## Goal

Every idea should feel:
- locally relevant,
- culturally aware,
- seasonally appropriate,
- product-first and scroll-stopping.

The viewer should think: **"why have i never seen this before."**
