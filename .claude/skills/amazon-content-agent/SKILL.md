---
name: amazon-content-agent
description: End-to-end Amazon content system from idea to shoot-ready output and production tracking. Use when the user asks for a full Amazon content drop, sprint, or batch in one go.
---

# Amazon Content Agent (End-to-End)

This skill runs the full Amazon content system in a single pass: idea, selection, hooks, Shoot Packs, batching, and tracker output.

When invoked, execute all 7 steps automatically. Do not ask for step-by-step confirmation. Return one consolidated response.

## Step 1: Idea generation

Generate 10 Amazon Finds product ideas for UAE and KSA.

Rules:
- Must be visually interesting.
- Must feel TikTok-native.
- Must solve a problem or create curiosity.

## Step 2: Selection

Select the top 5 ideas based on:
- Scroll-stopping potential
- Visual payoff
- Simplicity to shoot

Write a single short sentence for each, explaining why it made the cut.

## Step 3: Hook + Concept

For each of the 5 selected ideas, assign exactly one hook from the approved list (use exact wording, no shorthand):

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

Write:
- Hook (exact wording)
- Concept (1 line)

## Step 4: Shoot Pack

For each of the 5 ideas, produce a full Shoot Pack:

- Hook (from approved list)
- Concept (1 line)
- Shot list (3 to 5 simple shots)
- Filming notes (lighting, angle, setting)
- Creator instruction (delivery, pacing, performance)
- Ending / payoff (ties back to the hook, mentions UAE and KSA)

Rules:
- Must be shootable by 1 content creator.
- Must be simple. No crew, no studio.
- Must be visual-first. Let the visuals carry the story.

Follow the performance rules from `amazon-video-ideation`:
1. First shot creates confusion or tension.
2. Never open on a static product shot.
3. Include at least one interaction moment.
4. Include a pattern interrupt.
5. Ending must feel satisfying or surprising.
6. Do not over-explain.

## Step 5: Batching (shoot days)

Group the 5 Shoot Packs into shoot days by Shot Type. One setup per day.

Setup categories:
- Desk
- Kitchen
- Bathroom
- Outdoor

Minimise setup changes. Target 2 to 4 items per shoot day.

## Step 6: Production tracker output

Output a clean table with these columns:

| ID | Title | Market | Platform | Hook | Concept | Shot Type | Shoot Day | Status |

Set Status to "Ready to shoot" for every row.

## Step 7: Captions (Instagram + TikTok)

For every selected item, write two captions. One for Instagram, one for TikTok.

**Instagram caption rules:**
- Slightly more descriptive than TikTok.
- Max 2 lines.
- Clean, premium tone.
- Light CTA allowed (e.g. "UAE + KSA link below").

**TikTok caption rules:**
- Casual and reactive.
- Feels like a comment, not a brand line.
- Curiosity-driven.
- No formal CTA.

**Global caption rules:**
- Do not explain the product.
- Do not repeat the script.
- Reinforce the hook or the payoff.
- Keep it short and natural.

**Output format per item:**

```
Instagram:
[caption]

TikTok:
[caption]
```

## Step 8: Final output structure

Return the response in this order:

1. **Selected ideas summary** (5 items, one line each, with the reason for selection)
2. **Shoot Packs** (one full Shoot Pack per selected item)
3. **Production tracker table** (all 5 rows)
4. **Captions** (Instagram + TikTok, one block per item)

## Global rules

- Do not overcomplicate.
- Prioritise speed and clarity.
- Optimise for high-performing short-form video.
- Everything must be immediately usable by a creator.
- No custom hooks. Use the approved list in full wording.
- Every output is UAE + KSA by default.
