# zero-to-phd

A Claude Code skill that acts as your personal expert trainer. Give it any topic and a number of days, and it builds a Harvard/MIT-level, completely free, day-by-day learning plan that takes you from zero to confident practitioner.

## What it does

- Generates a structured N-day training plan for any topic
- Sources only 100% free resources (YouTube, MIT OCW, Harvard CS50, freeCodeCamp, official docs)
- Each day has morning + afternoon blocks, specific resources with links, and a hands-on mini-project
- Key Insight block per day — the mental model shift that separates beginners from experts
- Mermaid diagrams for learning arc and concept map (renders on GitHub)
- Visual time blocks and progress tracker
- Ends with a capstone project you can put in a portfolio
- Saves everything locally: full plan, printable cheat sheet, all links, projects folder

## Usage

```
/zero-to-phd Python 5
/zero-to-phd "Vector Databases" 7
/zero-to-phd n8n 3
/zero-to-phd
```

If you run it without arguments, it asks clarifying questions first.

## Prebuilt topic tracks

- Python (advanced track)
- SQL & Analytics
- Machine Learning / AI
- n8n (workflow automation)
- Vector Databases
- Any topic you provide

## What gets saved locally

Every run creates `~/zero-to-phd-courses/<topic>/`:

```
README.md      Full N-day training plan (your working document)
HANDOUT.md     One-page cheat sheet — print this
resources.md   All links organized by day
projects/      Save your daily builds here
```

## Installation

Copy the skill to your global Claude Code commands folder:

```bash
cp skills/zero-to-phd/SKILL.md ~/.claude/commands/zero-to-phd.md
```

Then use `/zero-to-phd` in any Claude Code session.

## Design principles

- No filler. Every hour has a specific task.
- Only free resources. No paywalls, no credit cards.
- Build something every day.
- Key Insight per day — not a summary, the actual mental model shift.
- Harvard/MIT quality bar.
- Real projects, not toy examples.
- Common Traps with Trap / Why / Fix format.
- Confidence Test with explicit pass/fail criteria.
