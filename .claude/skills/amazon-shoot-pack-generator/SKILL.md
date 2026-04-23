---
name: amazon-shoot-pack-generator
description: Turn selected content ideas into shoot-ready Shoot Packs for a solo creator. Use when the user has a list of planned ideas and needs the full shoot brief for each.
---

# Amazon Shoot Pack Generator

Purpose: turn selected ideas into shoot-ready content. One Shoot Pack per idea. No extras.

## Input

A list of selected content ideas. Each idea should include:
- Title or product
- Hook (from the approved list in `.claude/skills/production-tracker/SKILL.md`)
- Concept (1 line)
- Category (Finds or Now)
- Shot Type

## Output

One Shoot Pack per idea, with these 6 sections:

**1. Hook** — exact wording from the approved list.
**2. Concept** — one plain sentence.
**3. Shot list** — 3 to 5 numbered shots, one line each.
**4. Filming notes** — 2 to 4 bullets on lighting, angle, and setting.
**5. Creator instruction** — how to perform it: delivery, pacing, where to be silent, where to react.
**6. Ending / payoff** — the final beat. Must feel satisfying or surprising. Must mention UAE and KSA.

## Rules

- Must be shootable by 1 creator with a phone.
- Keep it simple. No crew, no studio required.
- Focus on visual storytelling. If the shot shows it, do not say it.
- First shot must create curiosity or tension. No static product opens.
- Include at least one interaction moment per pack (touch, press, poke, pour, reveal).
- Filming notes must be doable with natural light and basic framing.

## For Amazon Now ideas

- Use POV framing. Keep it real and in-the-moment.
- No polished setups. Messy kitchen counter is fine.
- Show the problem first, then the 15-minute solution.

## Format

Return all Shoot Packs in sequence. Label each clearly by ID or title. No preamble, no summary after.
