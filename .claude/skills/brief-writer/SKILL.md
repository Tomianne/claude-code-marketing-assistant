---
name: brief-writer
description: Turns rough campaign notes into a structured creative brief ready for a designer, copywriter, or agency. Trigger: "write a brief for X", "create a campaign brief", "brief this out", "draft a brief for [campaign name]"
argument-hint: "campaign name or description, goal, any known constraints or context"
allowed-tools: Read Write
---

# Skill: Brief Writer

## Purpose

Turn rough campaign thinking into a structured brief that a designer, copywriter, or agency can work from without needing a follow-up conversation.

---

## Step 1: Load context

Read:
- `context/brand-voice.md`
- `context/target-audience.md`
- `context/campaigns.md` (check if this campaign is already listed)

---

## Step 2: Gather missing information

If any of the following are genuinely unclear from the request, ask before writing. Only ask about information that is missing -- do not ask for things that can be reasonably inferred.

- What is the campaign trying to achieve? (awareness, leads, retention, launch announcement)
- Who specifically is it targeting -- is it the primary audience or a sub-segment?
- Which channels will it run on?
- Is there a deadline or budget to factor in?

---

## Step 3: Write the brief

Use this structure:

```
# Campaign Brief: [Campaign Name]
Date: YYYY-MM-DD

## 1. Objective
[One sentence. Include a metric if possible -- e.g. "Generate 20 qualified leads from manufacturing CFOs by end of Q3."]

## 2. Target audience
[Specific, not generic. Pull from target-audience.md and add any campaign-specific focus.]

## 3. Key message
[The single idea this campaign communicates. One sentence. If you can't say it in one sentence, it needs simplifying.]

## 4. Tone of voice
[Reference brand-voice.md + any campaign-specific tone adjustments.]

## 5. Channels and formats
[List each channel and what gets produced for it -- e.g. "LinkedIn: 3 posts. Email: 2-email sequence. Landing page: 1 page."]

## 6. Deliverables
[Bullet list of every asset that needs to be produced.]

## 7. Timeline
[Key dates: brief approved, assets delivered, campaign live, campaign ends.]

## 8. Success metrics
[How we know it worked. 2-3 specific measures.]
```

---

## Step 4: Save and present

Save to `projects/briefs/YYYY-MM-DD-[campaign-slug].md`

Present the brief in full. Ask: "Does this capture it, or anything to adjust?"
