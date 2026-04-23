---
name: amazon-client-sheet-exporter
description: Export internally approved Amazon content into a clean client-facing sheet. Final step in the Amazon content workflow. Only works on items that passed internal review.
---

# Amazon Client Sheet Exporter

Purpose: export approved content into a clean client-facing sheet. Seventh and final step.

## Input

- A list of items that passed `amazon-internal-reviewer` with status `Pass`.
- For each item: ID, category, product, hook, edited cut link, captions, Amazon UAE link, Amazon KSA link.

## Pre-check (mandatory)

- If any item is not `Pass`, do not include it. Flag at the top of the output: "Skipped: <IDs> (not internally approved)".
- If no items are `Pass`, return: "No items approved for export." Do nothing else.

## Output

One clean client-facing table:

| # | Category | Product | Hook | Concept | Edited Cut | Instagram Caption | TikTok Caption | Amazon UAE | Amazon KSA | Suggested Post Date |

## Rules

- Numbering starts at 1 and runs through the batch.
- No internal IDs in the client sheet.
- No internal notes, status columns, or QA flags.
- No work-in-progress items.
- Suggested Post Date is left blank if not provided.
- Captions go in full, exactly as written.
- Both Amazon UAE and Amazon KSA links required for every row.

## Tone

This is the client's view. Keep it polished, scannable, professional. No internal jargon.

## Do not include

- Production briefs
- Edit briefs
- Internal review notes
- Anything that did not pass internal review
