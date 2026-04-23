---
name: amazon-edit-handoff
description: Create a clear edit brief from shot footage and the production plan. Fourth step in the Amazon content workflow. Use after shooting is done.
---

# Amazon Edit Handoff

Purpose: hand shot footage to the editor with a clear edit brief. Fourth step. Cannot run without shot footage.

## Input

- The original Production Brief.
- A list of shot files or clip names.
- Notes from the shoot day (if any).

## Output

One Edit Brief per item:

**1. Item ID + product**
**2. Opening frame** — exact clip + timestamp + on-screen text.
**3. Cut sequence** — ordered list of clips with rough cut points.
**4. On-screen text** — what appears, when, for how long.
**5. Pacing** — tight or medium, target length in seconds.
**6. Music vibe** — one line. No specific track unless provided.
**7. Closing frame** — exact clip + UAE + KSA visible.
**8. Notes** — anything to flag (re-shoots needed, framing fixes).

## Rules

- Total length: 15 to 30 seconds for Finds, 20 to 40 seconds for Now.
- Cuts must move the story forward. No filler.
- Hook text must appear in the first 2 seconds.
- No watermarks. No third-party logos.
- Closing frame must show price and UAE + KSA mention.

## Do not include

- Captions (handled by `amazon-caption-writer`)
- Client comments
- Approval notes

## Hand-off

Edited cut feeds `amazon-caption-writer`, then `amazon-internal-reviewer`.
