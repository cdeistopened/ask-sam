# I Am Sam

876 episodes of My First Million (793) and MoneyWise (83), decomposed into frameworks and packaged as a Claude Code plugin. Sam Parr, Shaan Puri, and 500+ guests across deal evaluation, pricing, negotiation, hiring, wealth, content strategy, and life design.

18 skills. 134 framework articles. 38 people profiles. Entity intelligence. 773 searchable transcripts. Every quote traces to a source episode.

## Install

```bash
claude plugin add cdeistopened/i-am-sam
```

Or clone it:
```bash
git clone https://github.com/cdeistopened/i-am-sam.git ~/.claude/plugins/i-am-sam
```

## Skills

### Decision Skills (10)

You bring a real situation, the skill applies the relevant frameworks.

| Skill | Use when... |
|-------|------------|
| `idea-vetter` | You have a business idea to pressure-test |
| `acquisition-evaluator` | You want to buy a business |
| `exit-coach` | You're thinking about selling |
| `negotiation-coach` | You're preparing for a specific negotiation |
| `pricing-optimizer` | Your pricing needs work |
| `cold-outreach` | You need first customers |
| `hiring-framework` | You need to hire |
| `goal-architect` | You want to set goals or redesign your life |
| `wealth-allocator` | You have capital to deploy |
| `gauntlet` | Run a business idea through all 5 evaluation stages at once |

### Intelligence Skills (2)

| Skill | Use when... |
|-------|------------|
| `people-intel` | You want a dossier on anyone in Sam's network — episodes, quotes, relationships, draft intro |
| `content-miner` | You need content ideas from the archive — gaps, revisits, guest callbacks, clip discovery |

### Tutor Skills (4)

Guided learning through conversation. Each level has questions and exercises before moving on.

| Tutor | What it covers |
|-------|---------------|
| `business-fundamentals` | Thiel test, Hormozi value equation, unit economics, North Star formula, exit basics |
| `deal-making-masterclass` | Sourcing, valuation, deal structure, negotiation, selling |
| `wealth-mindset` | Enough number, wealth staircase, post-exit identity, giving and legacy |
| `negotiation-fundamentals` | Tactical empathy, calibrated questions, accusation audits, mirroring, MFM deal playbook |

### Utility

| Skill | Use when... |
|-------|------------|
| `i-am-sam` | General business questions — routes to the right skill |
| `episode-recommender` | Find episodes by topic or guest |

## The progression

```
/i-am-sam:business-fundamentals
    │
    ├── Got an idea?           → idea-vetter → gauntlet (full evaluation)
    ├── Want to buy?           → acquisition-evaluator
    │                               └── deal-making-masterclass
    ├── Need customers?        → cold-outreach
    ├── Pricing wrong?         → pricing-optimizer
    ├── Need to hire?          → hiring-framework
    ├── Ready to sell?         → exit-coach
    │                               └── wealth-allocator → wealth-mindset
    ├── Who is [person]?       → people-intel
    ├── Content ideas?         → content-miner
    ├── Learn negotiation?     → negotiation-fundamentals
    │                               └── negotiation-coach (bring a real deal)
    └── Life design            → goal-architect
```

## What's in the repo

| | Count |
|-|-------|
| MFM transcripts | 690 |
| MoneyWise transcripts | 83 |
| Framework articles | 134 |
| People profiles | 38 |
| Entity intelligence files | 2 |
| Indexes (topic, guest, framework) | 3 |
| Interactive skills | 18 |

## How it works

Three layers. Skills are the interactive coaching sessions. Reference articles are the 134 written framework guides (PE rollups, zero-dollar acquisitions, tactical empathy, emotional home framework, spending frameworks, etc.). Transcripts are the 773 polished episodes, searchable by grep.

You start with a skill. If you need more depth, the skill pulls from articles and people profiles. If you need a specific quote or want to explore something the articles don't cover, it searches transcripts and entity data.

## Credits

Source material: [My First Million](https://www.youtube.com/c/MyFirstMillionPod) by Sam Parr and Shaan Puri, plus [MoneyWise](https://www.youtube.com/@moneywise) by Sam Parr. The full archive is also browsable at [myfirstmillion.wiki](https://myfirstmillion.wiki).

Built by [Creative Intelligence Agency](https://creativeintel.agency).

This is an editorial reorganization of publicly available podcast content. Not affiliated with Sam Parr, Shaan Puri, or Hampton.
