---
name: amazon-client-sheet-exporter
description: Convert internally approved content into a clean client-facing sheet. Final step in the Amazon content workflow. Only runs on content with Approved status from amazon-internal-reviewer.
---

# Amazon Client Sheet Exporter

Purpose: convert internally approved content into a clean client-facing sheet format. Seventh and final step.

## Pre-check (mandatory)

- Only process items with `Approved` status from `amazon-internal-reviewer`.
- If any item is not `Approved`, skip it and note at the top: "Skipped: <IDs> — not internally approved."
- If no items are `Approved`, return: "No items approved for export." Do nothing else.

## Output

One row per approved item:

| Internal Content ID | Content Title | Market | Platform | Category | Final Caption | Final Product Link | Approval Status | Video Link | Notes |

## Field definitions

- **Internal Content ID** — e.g. AE-001, SA-003.
- **Content Title** — product name + hook in plain language.
- **Market** — UAE, KSA, or Both.
- **Platform** — Instagram, TikTok, or Both.
- **Category** — Amazon Finds or Amazon Now.
- **Final Caption** — platform-specific caption as written. One row per platform if captions differ.
- **Final Product Link** — Amazon UAE link and Amazon KSA link, both required.
- **Approval Status** — Approved.
- **Video Link** — leave as placeholder if not yet uploaded.
- **Notes** — leave blank unless there is a specific scheduling instruction or client note.

## Rules

- Client-facing output only. Clean and polished.
- No internal comments.
- No working notes.
- No draft language.
- No production jargon unless it is client-facing (e.g. "Amazon Now" is fine).
- Both UAE and KSA product links required on every row.
- Approval Status column shows `Approved` only — no other statuses reach this step.

## Do not include

- Production briefs
- Edit briefs
- Internal review notes
- Anything that did not pass internal review
