---
name: production-tracker
description: Track content through production stages for Amazon and Core42, from idea to posted. Use when the user wants to check or update content status, assign roles, or plan shoot days.
---

# Production Tracker

Operational tracker for both clients. Built so a real social team can run from it, not just read it.

## Stages

**Amazon (10 stages)**
1. Idea
2. Shortlisted
3. Scripted
4. Shoot planned
5. Raw footage uploaded
6. Edited
7. Sent for approval
8. Approved
9. Scheduled
10. Posted

**Core42 (6 stages)**
1. Idea
2. Drafted
3. Sent for approval
4. Approved
5. Scheduled
6. Posted

## Tracker fields

Every row must include:

- **ID** (e.g. AMZ-001, C42-001)
- **Client** (Amazon or Core42)
- **Title**
- **Market** (UAE, KSA, or UAE + KSA)
- **Platform** (TikTok, Instagram, YouTube, LinkedIn, or combo)
- **Product Link UAE** (Amazon only)
- **Product Link KSA** (Amazon only)
- **Shoot Day** (Amazon only, group content into shoot days with a date)
- **Social Manager** (owns overall delivery)
- **Producer** (Amazon only, owns shoot)
- **Editor** (owns post-production)
- **Current Stage**
- **Approval Status** (Not submitted / Pending client / Changes requested / Approved)
- **Next Action**
- **Due Date**

If a field does not apply (e.g. Core42 has no Shoot Day), mark it `N/A`.

## Roles (default team)

- **Social Media Manager:** runs the tracker, owns delivery end to end.
- **Producer:** owns pre-production through raw footage upload (Amazon).
- **Editor:** owns post-production and export.
- **Account Manager:** handles client approval loop.

Use real names once assigned. Do not use "TBC owner" once a project is live.

## Approval Status values

- **Not submitted** (still internal)
- **Pending client** (with client, waiting)
- **Changes requested** (client wants edits)
- **Approved** (green light to schedule)

## Output formats

### A. Summary table (for quick status reviews)

| ID | Title | Stage | Shoot Day | Approval | Next Action |
|---|---|---|---|---|---|

### B. Full card view (for detailed tracking)

```
ID: AMZ-001
Title: ...
Client: Amazon
Market: UAE + KSA
Platform: TikTok + Instagram Reels
Product Link UAE: ...
Product Link KSA: ...
Shoot Day: Day 1 (YYYY-MM-DD)
Social Manager: ...
Producer: ...
Editor: ...
Current Stage: Scripted (3/10)
Approval Status: Not submitted
Next Action: ...
Due Date: YYYY-MM-DD
```

Use the summary table for standups. Use the card view when assigning work or briefing a team member.

## Rules

- One stage per item.
- Move forward one stage at a time. No skipping.
- Never schedule before Approval Status is "Approved".
- Flag anything stuck in one stage for more than 5 days.
- Group Amazon shoots into the same day where possible to save production cost.
- Keep it current. A stale tracker is worse than no tracker.
