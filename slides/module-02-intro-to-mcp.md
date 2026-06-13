# Module 2 Slides: Introduction to MCP
## 🟢 Novice | Tech Writer's Tribe

---

## SLIDE 1 — Title

# Introduction to MCP
### The Universal Adapter for AI
#### Module 2 of 8 | 🟢 Novice Level

**Tech Writer's Tribe**
AI-Powered Documentation Mastery

---

## SLIDE 2 — Recap

# Quick Recap: Module 1

- AI is a **pattern completion engine**
- AI handles *form*; you handle *substance*
- The partnership model: You → AI → You → Output

> "Who used Claude for a real task this week?
> What happened?"

---

## SLIDE 3 — The Documentation Scaling Problem

# The Problem We're Solving

30 microservices. Every sprint, you must:

- Verify every endpoint is documented ✗
- Check parameter descriptions ✗
- Confirm error codes are listed ✗
- Validate examples work ✗
- Enforce style guide consistency ✗

**Human review doesn't scale.**
**Copy-paste checklists get stale.**
**Institutional knowledge walks out the door.**

---

## SLIDE 4 — What Is MCP?

# What Is MCP?

**Model Context Protocol** is an open standard that defines how AI models communicate with external tools and data sources.

---

## SLIDE 5 — The USB Analogy

# The USB Analogy

| Before USB | After USB |
|-----------|-----------|
| Every device: different connector | One protocol, every device |

| Before MCP | After MCP |
|-----------|-----------|
| Every AI integration: custom code | One protocol for all tools |
| Tools only work with one AI model | Any server works with any client |
| Breaks when models update | Protocol is stable and versioned |

---

## SLIDE 6 — The Three Parts of MCP

# The Three Parts of MCP

```
  MCP Client          MCP Protocol         MCP Server
  ──────────         ──────────────        ──────────
  Claude Desktop  ←──────────────────→   Your tool
  Cursor                                  ● Tools
  VS Code                                 ● Resources
                                          ● Prompts
```

1. **Client** — The AI application
2. **Server** — Your tool or system
3. **Protocol** — The standard they use to talk

---

## SLIDE 7 — Tools, Resources, Prompts

# What an MCP Server Provides

| Capability | What It Is | Example |
|-----------|-----------|---------|
| **Tools** | Functions AI can call | `check_completeness(file)` |
| **Resources** | Data AI can read | Your style guide, your glossary |
| **Prompts** | Reusable instruction templates | "Review for completeness" |

---

## SLIDE 8 — Claude Skills

# Claude Skills: Your Superpower

A **Claude Skill** is a markdown file in `.claude/commands/`

Run it with `/skill-name`

```
Simple Prompt          Skill (Reusable)        Agent (Autonomous)

"Fix this typo"        /check-api-doc          Full MCP Automation

Zero reuse             High reuse              Most powerful
Inconsistent           Consistent              Needs oversight
```

**Your sweet spot: Skills**

---

## SLIDE 9 — Why Writers Are Natural Skill Creators

# Technical Writers Are Natural Skill Creators

> "A skill is a well-structured instruction set.
> Writing clear instructions is literally your job."

You already:
- Write procedures others follow
- Structure information for clarity
- Anticipate what the reader needs
- Define what "done" looks like

**A skill does all of those things — but the reader is an AI.**

---

## SLIDE 10 — Skills vs. Tools

# Skills vs. Tools: Know the Difference

| | **Skills** | **Tools** |
|--|-----------|----------|
| What they are | Prompt templates | Code functions |
| Who builds them | Technical writers | Developers |
| Output type | AI-generated insights | Deterministic data |
| Best for | Review, generate, analyze | File access, computation |

---

## SLIDE 11 — Activity

# Activity: Skill or Tool?

For each task, decide: **Skill**, **Tool**, both, or neither?

1. Check if all API endpoints are documented
2. Generate a changelog from git history
3. Ensure headings use sentence case
4. Validate that code examples compile
5. Translate a doc into plain language
6. Count words in a document
7. Identify jargon a new user wouldn't understand
8. Compare two doc versions for regressions

---

## SLIDE 12 — Homework

# Before Module 3

1. **Read** Module 3 lesson (Prompt Engineering)
2. **Pick one repetitive documentation task**
3. **Write a paragraph** describing:
   - What the task is
   - What "done well" looks like
   - What criteria you'd use to judge quality

> That paragraph is the seed of your first skill.

---

## SLIDE 13 — Novice Checkpoint

# 🟢 Novice Checkpoint: Module 2

- [ ] Explain MCP using the USB analogy
- [ ] Distinguish Tool vs. Resource vs. Prompt
- [ ] Explain what a Claude Skill is without jargon
- [ ] Name 2 tasks in your workflow that could become skills
- [ ] Explain the difference between skill output and tool output

**Next: Module 3 — Prompt Engineering →**
