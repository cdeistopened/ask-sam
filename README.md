# Ask Sam

793 episodes of My First Million, decomposed into frameworks and packaged as a Claude Code plugin. Sam Parr, Shaan Puri, and about 500 guests across topics like buying businesses, pricing, negotiation, hiring, wealth, and life design.

14 skills. 134 articles. 794 searchable transcripts. Every quote traces to a source episode.

## Install

```bash
claude plugin add cdeistopened/ask-sam
```

Or clone it:
```bash
git clone https://github.com/cdeistopened/ask-sam.git ~/.claude/plugins/ask-sam
```

## Skills

Three tutors teach frameworks through guided conversation. They ask questions before giving answers, and each level has an exercise you do before moving on.

| Tutor | What it covers |
|-------|---------------|
| `business-fundamentals` | Thiel test, Hormozi value equation, unit economics, North Star formula, exit basics |
| `deal-making-masterclass` | Sourcing, valuation, deal structure, negotiation, selling |
| `wealth-mindset` | Enough number, wealth staircase, post-exit identity, giving and legacy |

Nine decision coaches walk you through a specific problem. You bring a real situation, they apply the relevant framework.

| Coach | Use when... |
|-------|------------|
| `idea-vetter` | You have a business idea |
| `acquisition-evaluator` | You want to buy a business |
| `exit-coach` | You're thinking about selling |
| `negotiation-coach` | You're preparing for a negotiation |
| `pricing-optimizer` | Your pricing needs work |
| `cold-outreach` | You need customers |
| `hiring-framework` | You need to hire |
| `goal-architect` | You want to set goals or redesign your life |
| `wealth-allocator` | You have capital to deploy |

Two utilities round it out: `ask-sam` routes general questions to the right skill, and `episode-recommender` finds episodes by topic or guest.

## How it works

The plugin has three layers. Skills are the interactive coaching sessions. Articles are the 134 written framework guides (PE rollups, zero-dollar acquisitions, emotional home framework, spending frameworks, etc.). Transcripts are the raw 794 episodes, searchable by grep.

You start with a skill. If you need more depth, the skill pulls from articles. If you need a specific quote or want to explore something the articles don't cover, it searches transcripts.

## The progression

```
/ask-sam:business-fundamentals
    │
    ├── Got an idea?        → idea-vetter
    ├── Want to buy?        → acquisition-evaluator
    │                            └── deal-making-masterclass
    ├── Need customers?     → cold-outreach
    ├── Pricing wrong?      → pricing-optimizer
    ├── Need to hire?       → hiring-framework
    ├── Ready to sell?      → exit-coach
    │                            └── wealth-allocator
    └── Life design         → goal-architect
                                 └── wealth-mindset
```

## What's in the repo

| | Count |
|-|-------|
| Episode transcripts | 794 |
| Framework articles | 134 |
| People profiles | 38 |
| Indexes (topic, guest, framework) | 3 |
| Interactive skills | 14 |

Total size is about 45MB, mostly transcripts.

## Planned integrations

- Gmail - `cold-outreach` drafts emails, `negotiation-coach` drafts responses
- Google Sheets - `wealth-allocator` builds allocation sheets, `goal-architect` builds tracking sheets
- Calendar - `goal-architect` sets annual review reminders
- Web scraping - `idea-vetter` pulls competitor data, `acquisition-evaluator` finds listings

## Credits

Source material: [My First Million](https://www.youtube.com/c/MyFirstMillionPod) by Sam Parr and Shaan Puri, plus 83 episodes of MoneyWise. The full archive is also browsable at [myfirstmillion.wiki](https://myfirstmillion.wiki), which has a Cortex intelligence layer (gap analysis, speaker timelines, topic maps) generated at build time.

This is an editorial reorganization of publicly available podcast content. Not affiliated with Sam Parr, Shaan Puri, or Hampton.
