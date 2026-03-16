# Ask Sam

An AI business coach built from 793 episodes of My First Million — the podcast where Sam Parr and Shaan Puri break down how people make money.

This is not a Sam Parr chatbot. It's a structured library of real frameworks, real quotes, and real methodologies from Sam, Shaan, and 500+ guests — packaged as interactive decision-making tools you can use in Claude Code.

## Who This Is For

Entrepreneurs at any stage:
- **Just starting out** — learn the core frameworks, validate your idea, get your first customers
- **Running a business** — optimize pricing, hire the right people, negotiate better deals
- **Thinking about what's next** — plan your exit, manage wealth, design your life

## Install

```bash
claude plugin add cdeistopened/ask-sam
```

Or clone manually:
```bash
git clone https://github.com/cdeistopened/ask-sam.git ~/.claude/plugins/ask-sam
```

## The Learning Path

```
START HERE
    │
    ▼
/ask-sam:business-fundamentals    ← Learn the core frameworks
    │
    ├── Got an idea? ──────── /ask-sam:idea-vetter
    ├── Want to buy? ──────── /ask-sam:acquisition-evaluator
    │                              └── /ask-sam:deal-making-masterclass
    ├── Need customers? ───── /ask-sam:cold-outreach
    ├── Pricing wrong? ────── /ask-sam:pricing-optimizer
    ├── Need to hire? ─────── /ask-sam:hiring-framework
    ├── Ready to sell? ────── /ask-sam:exit-coach
    │                              └── /ask-sam:wealth-allocator
    └── Life design ───────── /ask-sam:goal-architect
                                   └── /ask-sam:wealth-mindset
```

## 14 Skills

### Tutor Skills (structured learning)

| Skill | What You Learn |
|-------|---------------|
| `business-fundamentals` | The core frameworks — Thiel test, value equation, unit economics, North Star formula |
| `deal-making-masterclass` | How to buy, structure, negotiate, and exit deals |
| `wealth-mindset` | Money psychology — enough number, wealth staircase, post-exit identity, giving |

### Decision Skills (interactive coaching)

| Skill | When to Use |
|-------|------------|
| `idea-vetter` | You have a business idea and want to pressure-test it |
| `acquisition-evaluator` | You want to buy a business |
| `exit-coach` | You're thinking about selling your company |
| `negotiation-coach` | You're preparing for any negotiation |
| `pricing-optimizer` | Your pricing needs work |
| `cold-outreach` | You need customers |
| `hiring-framework` | You need to hire someone |
| `goal-architect` | You want to design your goals and life |
| `wealth-allocator` | You have capital to deploy |

### Utility

| Skill | What It Does |
|-------|-------------|
| `ask-sam` | Router — ask any question, get routed to the right skill |
| `episode-recommender` | Find the right episode to listen to |

## Example Conversations

**Validate an idea:**
```
> /ask-sam:idea-vetter
"I want to start a newsletter for CFOs"
→ Walks you through 6 filters: Thiel test, value equation, unit economics, validation plan...
```

**Buy a business:**
```
> /ask-sam:acquisition-evaluator
"I'm looking at buying a laundromat chain for $2M"
→ 7-phase evaluation: sourcing, valuation, deal structure, people diligence...
```

**Fix your pricing:**
```
> /ask-sam:pricing-optimizer
"My SaaS is $49/month and we're losing to competitors"
→ Patrick Campbell's 5-phase framework: diagnostic, add-ons, localization, packaging...
```

**Negotiate a deal:**
```
> /ask-sam:negotiation-coach
"I'm negotiating my salary with a new employer"
→ Chris Voss tactical empathy + Jeremy Gon same-side framing + Shaan's endgame tactics
```

**Design your life:**
```
> /ask-sam:goal-architect
"I just sold my company and feel lost"
→ Sam's 9-step system: Perfect Tuesday, floor/ceiling, anti-goals, Milly Awards...
```

**Learn the fundamentals:**
```
> /ask-sam:business-fundamentals
"I'm new to entrepreneurship, where do I start?"
→ Guided 5-level course from idea validation to exit planning
```

## How It Works

The plugin uses progressive disclosure — you don't need to read 794 transcripts:

1. **Ask a question** — Claude routes you to the right skill or framework
2. **Go deeper** — Claude reads the source article for more context
3. **Go deepest** — Claude searches across all 794 transcripts for related quotes and insights

Every framework traces back to specific episodes and specific quotes. Nothing is invented.

## What's Inside

| Content | Count |
|---------|-------|
| Episode transcripts | 794 |
| Framework articles | 134 |
| People profiles | 38 |
| Topic/guest/framework indexes | 3 |
| Interactive skills | 14 |

## Coming Soon

Future integrations that would make these skills even more powerful:

- **Gmail** — `cold-outreach` drafts actual cold emails; `negotiation-coach` drafts deal responses
- **Google Sheets** — `wealth-allocator` populates allocation spreadsheets; `goal-architect` creates tracking sheets
- **Calendar** — `goal-architect` sets review reminders (Milly Awards annual check-in)
- **Web scraping** — `idea-vetter` pulls competitor data; `acquisition-evaluator` finds listings

## Credits

Built from the [My First Million](https://www.youtube.com/c/MyFirstMillionPod) podcast by Sam Parr and Shaan Puri, plus 83 episodes of MoneyWise. Full searchable archive at [myfirstmillion.wiki](https://myfirstmillion.wiki).

This is an editorial reorganization of publicly available podcast content, not an official product of Sam Parr, Shaan Puri, or Hampton.
