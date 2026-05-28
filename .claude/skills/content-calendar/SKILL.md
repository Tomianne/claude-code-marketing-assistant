---
name: content-calendar
description: Plans a month of content across marketing channels. Reads active campaigns and audience context before planning. Trigger: "plan content for [month]", "create a content calendar for [month]", "what should I post in [month]", "plan my [channel] content for [month]"
argument-hint: "month, channels, any themes or campaign priorities"
allowed-tools: Read Write
---

# Skill: Content Calendar

## Purpose

Create a practical, channel-specific content plan for a given month. Output is a calendar with topic, format, and channel for each piece -- anchored to active campaigns and audience priorities.

---

## Step 1: Load context

Read:
- `context/target-audience.md`
- `context/campaigns.md`
- `CLAUDE.md` (check the Channels line under About Me)

---

## Step 2: Clarify scope

If any of the following are not clear from the request, ask:
- Which month?
- Which channels? (or default to the channels listed in CLAUDE.md)
- Any specific themes or campaigns to anchor the plan to?

---

## Step 3: Build the calendar

Format as a markdown table:

| Week | Date | Channel | Topic | Format | Campaign tie-in |
|---|---|---|---|---|---|

**Planning rules:**
- Anchor content to active campaigns listed in context/campaigns.md first
- Cover the audience journey across the month: mix of awareness, consideration, and conversion content
- LinkedIn: 3 posts per week maximum
- Email: 2 sends per month unless otherwise specified
- Vary content types within each channel -- not every post is a promotion
- Group related themes across channels in the same week for consistency
- Keep topic descriptions specific enough to act on ("How we helped a manufacturing firm cut reporting time by 40%" not "Case study")

---

## Step 4: Save the calendar

Save to `projects/strategy/YYYY-MM-[month]-content-calendar.md`

Present the full table. Ask: "Does this work, or any changes to the plan?"
