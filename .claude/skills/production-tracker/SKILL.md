---
name: production-tracker
description: Track content through production stages for Amazon and Core42 — from idea to raw footage, editing, approval, and scheduling. Use when the user wants to check or update content status.
---

# Production Tracker

Use this skill to track where each piece of content is in the pipeline.

## Stages

**Amazon**
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

**Core42**
1. Idea
2. Drafted
3. Sent for approval
4. Approved
5. Scheduled
6. Posted

## Tracker format

| ID | Client | Title | Current Stage | Owner | Next Action | Due Date |
|---|---|---|---|---|---|---|
| 001 | Amazon | ... | Edited | ... | Send to client | ... |
| 002 | Core42 | ... | Drafted | ... | Internal review | ... |

## What to do

- When asked for status: show the tracker, filtered by client if needed.
- When a stage changes: update "Current Stage", "Next Action", and "Due Date".
- Flag anything stuck in the same stage for more than 5 days.

## Rules

- One stage per item.
- Never skip stages — move step by step.
- Keep the tracker short and easy to read.
