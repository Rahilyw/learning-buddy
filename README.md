# Learning Buddy — Claude Code Skill

A Claude Code skill that acts as your **personal coding learning partner** — guiding you through programming problems using Socratic questioning and the **4Ds methodology**, without ever just handing you the answer.

Built for students, bootcamp learners, self-teachers, and anyone who wants to actually *understand* code, not just copy it.

---

## What it does

Instead of solving your problem for you, Learning Buddy:

- **Asks you to explain** what you're trying to do before writing a line of code
- **Guides with questions** — "What do you think this error is telling you?" instead of "Here's the fix"
- **Uses analogies** to build real intuition (linked lists as treasure hunts, recursion as Russian dolls)
- **Breaks down problems** into a checklist you tackle one step at a time
- **Celebrates wins** and honestly flags when something won't work — without being condescending

### The 4Ds Methodology

| D | What it means |
|---|---|
| **Delegation** | You explain what you're trying to do — keeps you in the driver's seat |
| **Description** | Claude explains the *how* and *why*, but you write the *what* |
| **Discernment** | Claude checks if you actually understand before moving on |
| **Diligence** | Before closing out, you explain *why* your solution works |

---

## Example

**Without the skill:**
> User: "My Python dict is crashing when I access a key"
> Claude: "The issue is a KeyError. Here are 3 ways to fix it: ..."

**With Learning Buddy:**
> User: "My Python dict is crashing when I access a key"
> Claude: "Let's figure it out together. Can you share the full error message? What do *you* think it's pointing at?"

---

## Install

### Option 1 — Skill file (easiest)

1. Download [`learning-buddy.skill`](./learning-buddy.skill)
2. In Claude Code, open the Skills panel and click **Install from file**

### Option 2 — Manual

1. Clone this repo (or just download the `learning-buddy/` folder)
2. Copy the `learning-buddy/` folder into your Claude skills directory:
   - **macOS/Linux:** `~/.claude/skills/`
   - **Windows:** `%APPDATA%\Claude\skills\`
3. Restart Claude Code — the skill will appear automatically

---

## When it triggers

Learning Buddy activates when you signal that you want to **understand**, not just solve:

**Triggers on phrases like:**
- "help me understand..."
- "walk me through..."
- "I don't just want the fix"
- "I want to learn why"
- "be my coding buddy / learning partner"

**Also triggers for:**
- Students (assignments, courses, professors, bootcamps, exams)
- Self-learners working through tutorials or coding challenges
- Interview prep (LeetCode, etc.) when you want to understand patterns
- Design/architecture questions framed as "how should I think about this?"

**Does NOT trigger for:**
- Quick one-off questions ("what does X mean?")
- Production/work engineering tasks
- Code review requests
- "Just give me the code" requests

---

## Scenarios it handles

| Situation | What Learning Buddy does |
|---|---|
| **Debugging** | Asks you to read the stack trace first, hypothesize the cause, then gives a directional hint |
| **New feature** | Breaks it into subtasks, asks you to define data structures first |
| **Totally stuck** | Gives a hint using a completely different scenario (different language, different domain) |
| **Frustrated** | Acknowledges it briefly, then redirects to a smaller tractable sub-problem |
| **Concept review** | Tests with progressively harder questions, escalates only once you're confident |

---

## Built with

- [Claude Code](https://claude.ai/code) skill system
- Socratic questioning methodology
- The 4Ds learning framework

---

*Made by [@rahilyw] https://github.com/Rahilyw) — Contributions and feedback welcome!*
