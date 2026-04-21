# zero-to-phd

> Give it a topic. Give it a number of days. Get a Harvard/MIT-level learning plan — free resources only, day by day, from zero to confident.

Built this because every "learning roadmap" I found was either a link dump or a paid course funnel. This one actually tells you what to do each hour.

---

## What you get

Type `/zero-to-phd Python 5` and it builds:

```
Day 1  Zero → Foundation      resources + hands-on build + self-test
Day 2  Foundation → Builder   resources + hands-on build + self-test
Day 3  Builder → Practitioner resources + hands-on build + self-test
Day 4  Practitioner → Expert  resources + hands-on build + self-test
Day 5  Expert → PhD           capstone project + confidence test
```

Everything saves locally to `~/zero-to-phd-courses/<topic>/`:

```
README.md      full plan with Mermaid diagrams
HANDOUT.md     one-page cheat sheet (print this)
resources.md   every link organized by day
projects/      your daily builds go here
```

---

## Quick start

```bash
# Install
cp skills/zero-to-phd/SKILL.md ~/.claude/commands/zero-to-phd.md

# Use
/zero-to-phd Python 5
/zero-to-phd "Vector Databases" 7
/zero-to-phd n8n 3
/zero-to-phd          # asks you questions first
```

---

## Topics with prebuilt resource sets

| Topic | What you'll be able to do after |
|-------|--------------------------------|
| Python | Build real scripts, automate tasks, read/write data |
| SQL & Analytics | Query any database, answer business questions |
| Machine Learning / AI | Train models, understand what's actually happening |
| n8n | Automate workflows without writing much code |
| Vector Databases | Build semantic search and RAG pipelines |
| Anything else | Provide any topic — it researches resources live |

---

## How each day is structured

Every day has the same shape:

- **Key Insight** — the one mental model shift that separates beginners from experts on this topic
- **Morning block** — core concepts with specific resources and timestamps
- **Afternoon block** — applied practice
- **Daily build** — something you made, not followed along with
- **Self-test** — 3 questions. Need 3/3 before moving on. If you score lower, there's a recovery protocol.

---

## What makes this different

Most learning plans are passive. This one isn't.

- Every hour has a specific task, not "explore the docs"
- Only free resources — no Udemy, no paywalls, no credit cards
- Concept map generated for every topic so you see the full picture before Day 1
- Adapts to your schedule: 1-2 hrs/day or 5+ hrs/day modes built in
- Ends with a confidence test you can only pass by actually building things
- Every plan closes with: open the first link right now, not tonight

---

## License

MIT
