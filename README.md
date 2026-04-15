# PM-learning-sam
Utilize the skills, instructions and prompts for the self learning as a Product Manager 

# AI PM Mastery — SKILL.md Instructions

## What This Is

`SKILL.md` is a structured teaching guide designed for AI coding assistants
(Claude, Cursor, etc.) to run interactively with Product Managers who want to
master AI concepts in 10 focused days.

---

## How to Use It

### Option 1 — Run it with Claude (Recommended)

1. Open [claude.ai](https://claude.ai) or any Claude interface.
2. Start a new conversation and paste the following:

```
I want to go through the 10-Day AI Mastery curriculum for Product Managers.
Please use the SKILL.md I'm attaching as your teaching guide.
Start from Day 1 unless I tell you otherwise.
```
or 

1. utilize the prompt available
2. view the pm learning prompt and review
3. adjust the prompt 

4. Upload or paste the contents of `SKILL.md` into the conversation.
5. Claude will teach each day interactively, including concepts, examples, and exercises.

---

### Option 2 — Install as a Claude Skill (Advanced)

If you're using Claude with Skills enabled:

1. Place the `SKILL.md` file in your Skills directory (e.g., `/mnt/skills/user/ai-pm-mastery/SKILL.md`).
2. Claude will automatically detect and trigger this skill when you ask:
   - "Teach me AI as a PM"
   - "Start my 10-day AI learning plan"
   - "Explain RAG to me"
   - "What should a PM know about LLM evals?"
   - Any day-specific topic (vibe coding, Claude Code, agents, etc.)

---

### Option 3 — Use in Cursor / Claude Code

1. Place `SKILL.md` in your project root or a `/skills/` folder.
2. In your `CLAUDE.md` (Claude Code project config), add:

```markdown
## Learning Resources
- `/skills/SKILL.md` — 10-Day AI Mastery curriculum for PM onboarding.
  Use this when the user asks about AI concepts, wants training, or asks
  about any of: LLMs, RAG, agents, evals, vibe coding, Claude Code.
```

3. Claude Code will reference it when relevant queries arise.

---

## Curriculum Overview

| Day | Topic |
|-----|-------|
| 1 | LLM Fundamentals & Context Engineering |
| 2 | RAG, Distillation, and AI PM Basics |
| 3 | Skills to Build AI Agents |
| 4 | Fundamentals of Claude Code |
| 5 | LLM Evaluations |
| 6 | Google AI Studio & AI Tooling |
| 7 | Vibe Coding |
| 8 | Claude Code in Practice |
| 9 | OpenClaw for Product Managers |
| 10 | The Complete AI PM Roadmap |

---

## Who This Is For

- Product Managers new to AI who want structured, practical education.
- PMs transitioning into AI PM roles.
- Anyone in a product, strategy, or GTM role who works with AI engineering teams.
- Technical PMs who want to fill gaps in specific areas (just jump to that day).

---

## What You'll Be Able to Do After 10 Days

- Explain LLMs, RAG, and agents to engineers, stakeholders, and customers.
- Write effective system prompts and evaluate AI output quality.
- Use Claude Code and AI tools to prototype and analyze independently.
- Define evals for AI features before shipping.
- Build a personal AI PM toolkit with reusable prompt templates.
- Speak credibly about AI product tradeoffs: cost, latency, accuracy, trust.

---

## Customizing the Curriculum

The `SKILL.md` is plain Markdown. You can:
- Add company-specific examples to any day.
- Swap the "Practical Exercise" for exercises relevant to your product domain.
- Extend Day 10 with your team's internal AI roadmap.
- Add new days for topics like AI FinOps, AI governance, or multimodal products.

---

## File Structure

```
AI-PM-Mastery/
├── SKILL.md          ← The curriculum (teach this to Claude)
└── README.md         ← This file (how to use it)
```
