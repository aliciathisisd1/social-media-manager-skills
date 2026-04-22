---
name: production-tracker
description: Track content through a lean creator-led workflow for Amazon and Core42, from idea to scheduled. Use when the user wants to check or update content status, assign hooks, or plan shoots.
---

# Production Tracker (Creator-Led)

Operational tracker built for a small, creator-led team. No heavy production chain. One social manager plans, one content creator shoots, one editor finishes.

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

Only three roles. Keep it lean.

- **Social Manager:** owns the tracker, the calendar, client comms, and final scheduling.
- **Content Creator:** owns sourcing, scripting, and shooting. Creator-led, not crew-led.
- **Editor:** owns post-production and delivery of the final cut.

Do not add Producer, Account Manager, or other roles unless the user explicitly asks.

## Tracker fields

Every row must include:

- **ID** (e.g. AMZ-001, C42-001)
- **Client** (Amazon or Core42)
- **Title**
- **Market** (UAE, KSA, or UAE + KSA)
- **Platform** (TikTok, Instagram, YouTube, LinkedIn, or combo)
- **Product Link UAE** (Amazon only)
- **Product Link KSA** (Amazon only)
- **Hook** (must match the approved hooks list below)
- **Concept (1 line)** (simple, plain-English description of the video)
- **Shot Type** (Desk, Kitchen, Bathroom, Outdoor, POV, Close-up, or combo)
- **Shoot Day** (Amazon only, group items into the same shoot day where possible)
- **Social Manager**
- **Content Creator**
- **Editor**
- **Current Stage**
- **Approval Status** (Not submitted / Pending client / Changes requested / Approved)
- **Next Action**
- **Due Date**

If a field does not apply (e.g. Core42 has no Product Link), mark it `N/A`.

## Approved hooks list

Every Amazon video must use one of these hooks. Do not invent new hooks unless the user explicitly approves one.

1. **POV hook:** "POV: [everyday situation]"
2. **Regret hook:** "If you don't own this by [time], you'll regret it"
3. **Geo hook:** "Tell me you live in [UAE/KSA/Dubai/Riyadh] without telling me"
4. **List hook:** "3 Amazon Finds you didn't know you needed"
5. **Sign hook:** "This is your sign to buy [product]"
6. **Curiosity hook:** "Wait, how does that even work?"
7. **Price hook:** "Under [X] dirhams and honestly worth it"
8. **Stop-scroll hook:** "Stop scrolling, you need this"

If a creator wants a hook outside this list, the Social Manager must approve it first and the tracker should note `Custom (approved)`.

## Approval Status values

- **Not submitted** (internal only)
- **Pending client** (with client, waiting)
- **Changes requested** (client wants edits)
- **Approved** (green light to schedule)

## Output formats

### A. Summary table (standups)

| ID | Title | Hook | Shot Type | Stage | Approval | Next Action |
|---|---|---|---|---|---|---|

### B. Full card view (detailed briefing)

```
ID: AMZ-001
Title: ...
Client: Amazon
Market: UAE + KSA
Platform: TikTok + Instagram Reels
Product Link UAE: ...
Product Link KSA: ...
Hook: Regret hook
Concept (1 line): ...
Shot Type: Outdoor + POV
Shoot Day: Day 1 (YYYY-MM-DD)
Social Manager: ...
Content Creator: ...
Editor: ...
Current Stage: Ready to shoot (5/10)
Approval Status: Not submitted
Next Action: ...
Due Date: YYYY-MM-DD
```

Use the summary for daily check-ins. Use the card view when briefing the creator or editor.

## Rules

- One stage per item. Move forward one stage at a time.
- Never schedule before Approval Status is "Approved".
- Every Amazon video uses one hook from the approved list.
- Every row has a filled Concept and Shot Type before moving to stage 5 (Ready to shoot).
- Group Amazon shoots into the same Shoot Day where possible.
- Flag anything stuck in one stage for more than 5 days.
- Keep it current. A stale tracker is worse than no tracker.
