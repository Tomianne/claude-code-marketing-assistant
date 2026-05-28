---
name: email-writer
description: Drafts marketing or outreach emails in your brand voice. Output is a markdown draft saved to projects/email/drafts/. No sending. Trigger: "draft an email about X", "write a marketing email for X", "write an outreach email to X", "write a nurture email"
argument-hint: "email type (marketing/outreach/newsletter), topic, audience or recipient"
allowed-tools: Read Write
---

# Skill: Email Writer

## Purpose

Write a complete marketing or outreach email in the brand voice. Draft only -- never send.

---

## Step 1: Load context

Read:
- `context/brand-voice.md`
- `context/target-audience.md`

---

## Step 2: Identify the email type

**Marketing email** -- sent to a list (newsletter, nurture, announcement):
- Tone: educational or value-first, one clear message
- Structure: subject line + preview text + body + single CTA

**Outreach email** -- sent to a specific person:
- Tone: direct, personal, not templated
- Structure: personalised hook + relevant pain point + what you offer + low-friction CTA

If the type is not clear from the request, ask before writing.

---

## Step 3: Write the email

**Rules:**
- Subject line: under 50 characters, specific rather than clever
- Preview text: one sentence that builds on the subject line (not a repeat of it)
- Body: short paragraphs, 2-3 sentences each -- one idea per paragraph
- CTA: one clear action only -- not three options
- No em dashes
- UK English
- Reflect tone from brand-voice.md
- Frame the message around what matters to the audience in target-audience.md

---

## Step 4: Save the draft

Save to `projects/email/drafts/YYYY-MM-DD-[topic-slug].md`

Structure the file as:
```
Subject: [subject line]
Preview: [preview text]

---

[Full email body]
```

---

## Step 5: Present and confirm

Show the full email. Ask: "Ready to use, or anything to change?"
