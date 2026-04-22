---
name: production-tracker
description: Track content through a lean creator-led workflow for Amazon and Core42, from idea to scheduled. Use when the user wants to check or update content status, assign hooks, or plan shoots.
---

# Production Tracker (Creator-Led)

Operational tracker built for a single in-house content creator. No heavy production chain. One social manager plans, one content creator shoots, one editor finishes.

## Stages

**Amazon (10 stages)**
1. Idea
2. Selected
3. Ordered
4. Scripted
5. Ready to shoot
6. Shot
7. Edited
8. Client review
9. Approved
10. Scheduled

**Core42 (6 stages)**
1. Idea
2. Drafted
3. Sent for approval
4. Approved
5. Scheduled
6. Posted

## Roles

Only three roles. No Producer. No Account Manager.

- **Social Manager:** owns the tracker, calendar, client comms, and scheduling.
- **Content Creator:** owns sourcing, scripting, and shooting. Creator-led, not crew-led.
- **Editor:** owns post-production and delivery of the final cut.

## Tracker columns

Every row must include all of these, in this order:

- ID
- Title
- Market (UAE / KSA / UAE + KSA)
- Platform
- Hook (must match the approved hooks list, written out fully)
- Concept (1 line)
- Shot Type (Desk / Kitchen / Bathroom / Outdoor / POV / Close-up, or combo)
- Product Link UAE
- Product Link KSA
- Shoot Day
- Social Manager
- Content Creator
- Editor
- Current Stage
- Approval Status
- Next Action
- Due Date

If a field does not apply (e.g. Core42 has no Product Link), mark it `N/A`.

## Approved hooks list (MANDATORY)

Every Amazon video uses exactly one hook from this list. Write it out in full. Do not shorten, rename, or describe it as a "type".

1. nobody mentions this
2. i wish i knew this earlier
3. pause for a second
4. ever notice this pattern
5. here's the real truth
6. let me save you hours
7. this may surprise you
8. you need this now
9. you may not agree with this
10. i just figured this out

Rules:
- One hook per video. Exact wording.
- No custom hooks unless the Social Manager has explicitly approved one. Mark as `Custom (approved)`.
- Never label a hook as "curiosity hook" or similar shorthand.

## Approval Status values

- Not submitted
- Pending client
- Changes requested
- Approved

## Output formats

### A. Summary table (standups)

| ID | Title | Hook | Shot Type | Stage | Approval | Next Action |
|---|---|---|---|---|---|---|

### B. Full card view (briefing)

```
ID: AMZ-001
Title: ...
Client: Amazon
Market: UAE + KSA
Platform: TikTok + Instagram Reels
Hook: pause for a second
Concept (1 line): ...
Shot Type: Desk + Close-up
Product Link UAE: ...
Product Link KSA: ...
Shoot Day: Day 1 (YYYY-MM-DD)
Social Manager: ...
Content Creator: ...
Editor: ...
Current Stage: Ready to shoot (5/10)
Approval Status: Not submitted
Next Action: ...
Due Date: YYYY-MM-DD
```

## Rules

- One stage per item. Move forward one step at a time.
- Never schedule before Approval Status is "Approved".
- Every Amazon video uses one hook from the approved list, written out in full.
- Every row has a filled Concept and Shot Type before stage 5 (Ready to shoot).
- Group Amazon shoots into the same Shoot Day where possible (see `amazon-content-calendar`).
- Flag anything stuck in one stage for more than 5 days.
- Keep it current. A stale tracker is worse than no tracker.
