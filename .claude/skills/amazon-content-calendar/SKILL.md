---
name: amazon-content-calendar
description: Plan Amazon shoot days by batching content by shot type, manage client approval, and schedule approved videos. Use when the user wants to plan a shoot, batch content, or schedule approved posts.
---

# Amazon Content Calendar

Use this skill for Amazon workflow steps 5, 8, and 9: shoot planning (batched), client approval, and scheduling.

## Batching rule

Group content by Shot Type so each shoot day needs minimal setup changes. One shoot day equals one setup where possible.

Primary setup categories:
- **Desk setups** (e.g. levitating plant pot, keychain cables, self-stirring mug on a desk)
- **Kitchen setups** (e.g. onion goggles, kitchen gadgets, countertop demos)
- **Outdoor setups** (e.g. misting fan, car seat gap filler, travel gear)

Rules for each shoot day:
- Stick to one setup category.
- Keep lighting, props, and location consistent across the day.
- Cover as many products as practical in that single setup.
- If an item needs a different setup (e.g. Bathroom, high-rise window, specialist location), give it its own shoot day. Do not mix setups unless setup time is genuinely zero.

Target batch size: 2 to 4 products per shoot day.

## What to do

1. **Plan the shoot (step 5)**
   - Pull all items at stage 4 (Scripted) or stage 5 (Ready to shoot) from `production-tracker`.
   - Group them by Shot Type into shoot days.
   - For each shoot day list: date, setup category, location, products, props, talent.
   - Example:
     - Shoot Day 1 (Desk): AMZ-003, AMZ-007 at home studio desk.
     - Shoot Day 2 (Outdoor): AMZ-001, AMZ-005 at rooftop.
     - Shoot Day 3 (Kitchen): AMZ-006, AMZ-009 at kitchen counter.

2. **Send for client approval (step 8)**
   - Package the edited video, caption, and hashtags.
   - Update Approval Status in `production-tracker` to "Pending client".

3. **Approve and schedule (step 9)**
   - Once "Approved", assign post date, time, and platform.
   - Move Current Stage to "Scheduled".

## Calendar entry format

| Product ID | Title | Shoot Day | Setup | Post Date | Platform | Caption (short) | Status |
|---|---|---|---|---|---|---|---|

## Rules

- One setup per shoot day where possible.
- One status per item at a time.
- Never schedule before Approval Status is "Approved".
- Always include both Amazon UAE and Amazon KSA links in the caption.
- Keep each shoot day tight: 2 to 4 products, under one production day.
- If setup time grows, split into two shoot days rather than compromise the look.
