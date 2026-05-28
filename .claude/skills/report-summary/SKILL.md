---
name: report-summary
description: Summarises a marketing report, analytics export, or data dump into an executive summary with key insights and recommended actions. Trigger: "summarise this: [paste content]", "summarise this report", "what does this data tell me", "pull insights from this"
argument-hint: "paste the report text or data directly into your message"
allowed-tools: Read Write
---

# Skill: Report Summary

## Purpose

Turn raw marketing data, analytics exports, or long reports into a short executive summary with clear insights and practical next steps. For a decision-maker, not an analyst.

---

## Step 1: Identify what was shared

The user will paste data, a report, or text into their message. Accept any format: a table of numbers, a paragraph summary, a GA4 export, campaign results, email metrics.

If nothing was pasted, ask: "Please paste the report or data you want me to summarise."

---

## Step 2: Write the summary

Use this structure:

```
## Overview
[2-3 sentences. What period does this cover? What was the overall result -- up, down, or flat?]

## What worked
[2-3 bullet points with specific evidence from the data. Numbers where available.]

## What did not work
[2-3 bullet points with specific evidence. Be direct.]

## Key insights
[3-5 observations that explain the patterns -- not just what happened, but why it likely happened and what it means.]

## Recommended actions
[3-5 specific, practical next steps. Actionable, not vague.]
```

**Rules:**
- Only reference what is actually in the data -- no invented benchmarks or industry comparisons unless the user provided them
- If the data is incomplete or a comparison cannot be made fairly, flag it explicitly
- Keep language plain -- avoid analyst jargon
- If the data is too vague to draw conclusions, say so and ask for more context before proceeding

---

## Step 3: Output

If the summary is over 200 words, offer to save it:
"Want me to save this to projects/strategy/?"

If yes, save to `projects/strategy/YYYY-MM-DD-report-summary.md`

Otherwise present it in the conversation.
