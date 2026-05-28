---
name: linkedin
description: Writes a LinkedIn post in your brand voice. Reads context/brand-voice.md and context/target-audience.md before writing. Saves output to projects/linkedin/. Trigger: "write a LinkedIn post about X", "draft a LinkedIn post on X", "post about X on LinkedIn"
argument-hint: "topic, company page or personal profile, any key points to include"
allowed-tools: Read Write
---

# Skill: LinkedIn Post Writer

## Purpose

Write a LinkedIn post that sounds specific to the brand -- not a template, not AI-flavoured. Every post has a strong opening line, one clear idea, and a natural close.

---

## Step 1: Load context

Read:
- `context/brand-voice.md`
- `context/target-audience.md`

---

## Step 2: Clarify if needed

If not specified, ask: "Is this for the company page or your personal profile?"

If the topic is genuinely too vague to write anything, ask one clarifying question. If the topic is workable, proceed without asking.

---

## Step 3: Write the post

**Format rules:**
- Opening line: a strong hook -- a bold claim, a specific observation, or a direct question. Never start with "I'm excited to share", "Thrilled to announce", or "Pleased to" anything.
- Body: 3-5 short paragraphs or bullet points. One idea per line. White space matters on LinkedIn.
- Close: either a question that invites comments, or a soft CTA (one action only)
- Length: 150-300 words for most posts. Do not pad.
- Hashtags: 2-3 relevant ones at the end only
- UK English
- No em dashes
- Reflect the tone attributes from brand-voice.md
- Write for the audience profile in target-audience.md -- use language that resonates with their world

---

## Step 4: Save the draft

Save to `projects/linkedin/YYYY-MM-DD-[topic-slug].md`

Add at the top of the file:
```
Post type: [Company page / Personal]
Status: Draft
Date: YYYY-MM-DD
```

---

## Step 5: Present and confirm

Show the post in full. Ask: "Happy with this, or any changes?"
