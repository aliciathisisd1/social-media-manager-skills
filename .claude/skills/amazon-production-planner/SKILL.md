---
name: amazon-production-planner
description: Turn approved content ideas into creator-ready production plans. Third step in the Amazon content workflow. Requires content ideas as input.
---

# Amazon Production Planner

Purpose: turn approved content ideas into creator-ready production plans. Third step. Cannot run without approved ideas.

## Input

A list of approved content ideas from `amazon-content-ideator`.

## Output

One Production Plan per idea:

**Internal Content ID:** (e.g. AE-001, SA-003)
**Hook:** (exact wording from approved list)
**Concept:** (1 sentence)
**Shot list:** (3 to 5 numbered shots, one line each)
**Filming notes:** (2 to 4 bullets — light, angle, setting)
**Creator instruction:** (delivery, pacing, where to stay silent, where to react)
**Ending / payoff:** (final beat — must mention UAE and KSA)
**Shoot day grouping:** (e.g. "Batch with other Kitchen shots")

## Rules

- Must be shootable by 1 creator with a phone.
- Must be simple and fast to execute.
- Real environments only. No studio.
- Product must be clearly visible throughout.
- Benefit must be obvious without explanation.
- Environment must be clean and culturally appropriate for UAE or KSA.
- First shot must create curiosity or tension. No static product opens.
- Include at least one interaction moment (touch, press, pour, reveal, peel).
- Natural light and basic framing only.

## Shoot day grouping rule

At the end of the full batch, group all items by shot type so the creator can batch-shoot efficiently:

- Kitchen day
- Desk day
- Bathroom day
- Outdoor day
- POV day

Only include groups that exist in the batch.

## Amazon Now plans

- POV framing throughout.
- Show problem first, then the 15-minute fix.
- In-the-moment feel. No cleaning up before filming.

## Do not include

- Edit instructions
- Captions
- Client-facing summaries

## Hand-off

After shooting, raw footage feeds `amazon-edit-handoff`.
