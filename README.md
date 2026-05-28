# Marketing AI Assistant -- Starter Pack

A personal AI marketing assistant built on Claude Code. Set it up once with your brand context and it knows your voice, your audience, and your priorities permanently -- no re-briefing, no copy-pasting guidelines into every chat.

---

## What is included

- `/setup` -- one-time onboarding wizard that creates all your personalised context files
- 5 skills: LinkedIn post writer, email writer, brief writer, content calendar, report summariser
- 2 agents: content agent, strategy agent

---

## Requirements

- [VSCode](https://code.visualstudio.com) -- free
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) -- `npm install -g @anthropic-ai/claude-code`
- A Claude account (Pro or API) -- [claude.ai](https://claude.ai)

---

## Setup (5 minutes)

1. Download and extract this folder
2. Open the folder in VSCode
3. Open the terminal (`Ctrl+`` ` on Windows / `Cmd+`` ` on Mac)
4. Run `claude` to start Claude Code
5. Run `/setup`
6. Answer 8 questions about your brand and role
7. Your assistant is ready

---

## How to use it

Once set up, open the folder in VSCode, run `claude`, and talk to it naturally:

**Content:**
- "Write a LinkedIn post about our new service launch"
- "Draft a newsletter email about our Q3 results"
- "Plan my LinkedIn content for August"

**Planning:**
- "Write a brief for our summer awareness campaign"
- "Summarise this: [paste your report or data]"

**Via agents (if you prefer not to remember skill names):**
- "Content agent: write a LinkedIn post about our pricing change"
- "Strategy agent: write a brief for our Q4 lead gen push"

---

## Updating your context

Your context files live in the `context/` folder. Edit them any time:

- `context/brand-voice.md` -- update if your tone evolves or you add avoid rules
- `context/target-audience.md` -- update if you move into a new segment
- `context/campaigns.md` -- keep this current as campaigns start and end

The assistant reads these files at the start of every task. No need to re-run setup.

---

## Watch the setup video

[Link to YouTube video -- AI with Hannah]

---

**GitHub:** https://github.com/Tomianne/claude-code-marketing-assistant

Built by Hannah Tomi Ajiboye | [AI with Hannah](https://youtube.com/@AIwithHannah)
