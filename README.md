# Learning Buddy — Claude Code Skill

![Claude Code](https://img.shields.io/badge/Claude_Code-skill-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Method](https://img.shields.io/badge/method-4Ds-purple?style=flat-square)

A Claude Code skill that acts as your **personal coding learning partner**, guiding you through programming problems using Socratic questioning and the **4Ds methodology**, without ever just handing you the answer.

Built for students, bootcamp learners, self-teachers, and anyone who wants to actually *understand* code, not just copy it.

---

## What it does

Instead of solving your problem for you, Learning Buddy:

- **Asks you to explain** what you're trying to do before writing a line of code
- **Guides with questions** "What do you think this error is telling you?" instead of "Here's the fix"
- **Uses analogies** to build real intuition (linked lists as treasure hunts, recursion as Russian dolls)
- **Breaks down problems** into a checklist you tackle one step at a time
- **Celebrates wins** and honestly flags when something won't work, without being condescending

### The 4Ds Methodology

| D | What it means |
|---|---|
| **Delegation** | You explain what you're trying to do — keeps you in the driver's seat |
| **Description** | Claude explains the *how* and *why*, but you write the *what* |
| **Discernment** | Claude checks if you actually understand before moving on |
| **Diligence** | Before closing out, you explain *why* your solution works |

---

## Example

### The "Spoon-Fed" vs. "Learning Buddy" Experience

| ❌ Without the Skill | 💡 With Learning Buddy |
| :--- | :--- |
| **User:** My Python dict is crashing when I access a key. | **User:** My Python dict is crashing when I access a key. |
| **Claude:** The issue is a KeyError. Here are 3 ways to fix it: `[Spits out code]` | **Claude:** Let's figure it out together. What does the error message say, and what do you think it's pointing at? |
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

## 🛠️ Scenarios & How It Handles Them

| Situation | Learning Buddy's Response |
| :--- | :--- |
| **Debugging a crash** | Asks you to read the stack trace, hypothesize the cause, and only *then* gives a directional hint. |
| **Architecting a new feature** | Breaks the feature into subtasks and asks you to define your data structures/schema first. |
| **Totally stuck** | Provides a conceptual hint using a completely different scenario, language, or domain. |
| **Frustrated** | Acknowledges the pain point warmly, then redirects you to a smaller, more tractable sub-problem. |
| **Concept Review** | Tests your knowledge with progressively harder questions, escalating only when you show confidence. |
---

## Built with

- [Claude Code](https://claude.ai/code) skill system
- Socratic questioning methodology
- The 4Ds learning framework

---

*Made by [@rahilyw] https://github.com/Rahilyw) — Contributions and feedback welcome!*
