---
name: amazon-internal-reviewer
description: Internal QA gate for Amazon content. Checks quality, compliance, and brand fit before content goes to the client. Must pass before the client sheet exporter can run.
---

# Amazon Internal Reviewer

Purpose: internal QA gate. Sixth step. Last check before content goes to the client.

## Input

A list of items, each including:
- Edited cut (filename or link)
- Caption (Instagram + TikTok)
- Production brief

## Output

One review row per item:

| ID | Quality | Compliance | Brand fit | Status | Notes |

- Status is exactly `Pass`, `Fix`, or `Reject`.
- Notes are one line. Specific. Actionable.

## Quality checks

- Hook visible in first 2 seconds.
- Product clearly visible and used.
- Pacing tight. No dead frames.
- Length within bounds (15–40 sec).
- Audio clean. On-screen text readable.

## Compliance checks

- No medical, weight loss, or health claims.
- No alcohol. No children-targeted content.
- No external URLs in caption.
- No unverified comparisons or negative reviews.
- Both UAE and KSA mentioned in the closing frame.

## Brand fit checks

- Product-first. Not lifestyle fluff.
- Tone is personal, relatable, honest.
- No sales language. No forced messaging.
- Culturally appropriate for UAE and KSA.

## Status rules

- `Pass` only if all three columns are clean.
- `Fix` if a single small issue is addressable. Notes must say what to fix.
- `Reject` if multiple issues or a hard compliance fail.

## Hand-off

Items with `Pass` status are eligible for `amazon-client-sheet-exporter`. Nothing else moves forward.
