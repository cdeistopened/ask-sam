# I Am Sam

A Claude Code plugin built from 876 episodes of [My First Million](https://www.youtube.com/c/MyFirstMillionPod) and [MoneyWise](https://www.youtube.com/@moneywise). Business frameworks, deal evaluation tools, people intelligence, and 773 searchable transcripts — all grounded in specific episodes and real quotes.

18 skills. 134 framework articles. 38 people profiles. Entity intelligence.

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/cdeistopened/i-am-sam.git
```

### 2. Add it to Claude Code

In your project's `.claude/settings.json`:

```json
{
  "plugins": [
    "/path/to/i-am-sam"
  ]
}
```

Or add it globally in `~/.claude/settings.json` to make it available in every project.

### 3. Restart Claude Code

The plugin loads on startup. After adding the path, restart your Claude Code session.

### 4. (Optional) Index with QMD for better retrieval

If you have [QMD](https://github.com/cdeistopened/qmd) installed, indexing the transcripts gives Claude semantic search over the full archive instead of relying on grep:

```bash
# Add to your ~/.config/qmd/index.yml:
# i-am-sam-transcripts:
#   path: /path/to/i-am-sam/references/transcripts
#   glob: "**/*.md"

qmd reindex i-am-sam-transcripts
qmd embed i-am-sam-transcripts
```

This is optional — the plugin works without it, using indexes and grep. But QMD makes cross-archive questions ("every time someone mentioned PE rollups across all 876 episodes") significantly faster and more accurate.

## Try it

```
I have an idea for a premium dog food subscription box. Run the gauntlet.
```

This runs the idea through 5 evaluation stages — idea validation, market sizing, pricing architecture, team blueprint, exit lens — each with pass/fail criteria drawn from specific MFM frameworks.

Other good starting questions:

- "I'm thinking about buying a laundromat chain for $1.2M — is it a good deal?"
- "Build me a dossier on Alex Hormozi — every episode, key quotes, who he's connected to"
- "Help me prepare for a negotiation with my landlord"
- "What topics have been mentioned across many episodes but never got a deep dive?"
- "How should I deploy $500K in capital?"

## Skills

### Decision Skills (10)

Bring a real situation, get a structured evaluation.

| Skill | What it does |
|-------|-------------|
| `idea-vetter` | Pressure-test a business idea (Thiel test, Hormozi value equation, unit economics) |
| `acquisition-evaluator` | Evaluate a business to buy (PE rollups, main street, SaaS) |
| `exit-coach` | Plan a company sale (timing, valuation, deal structure) |
| `negotiation-coach` | Prepare for a specific negotiation (Voss, Gon, Suli Ali) |
| `pricing-optimizer` | Set or fix pricing (ProfitWell frameworks, add-on strategy) |
| `cold-outreach` | Get first customers with direct outreach |
| `hiring-framework` | Make a hiring decision (role-specific interview design) |
| `goal-architect` | Design goals (Dyrdek life accounting, Wilkinson systems) |
| `wealth-allocator` | Deploy capital (Howard Marks, Pabrai, TIGER 21) |
| `gauntlet` | Run all 5 evaluation stages sequentially — the "run everything" skill |

### Intelligence Skills (2)

| Skill | What it does |
|-------|-------------|
| `people-intel` | Dossier on anyone in the archive — episodes, quotes, co-occurrence, relationships |
| `content-miner` | Find content opportunities — topic gaps, revisit-worthy predictions, guest callbacks, clip discovery |

### Tutor Skills (4)

Guided learning. Each level has questions and exercises.

| Skill | What it covers |
|-------|---------------|
| `business-fundamentals` | Unit economics, distribution, moats, market timing, exit basics |
| `deal-making-masterclass` | Sourcing, valuation, deal structure, negotiation, selling |
| `wealth-mindset` | Wealth stages, post-exit identity, spending frameworks, giving |
| `negotiation-fundamentals` | Tactical empathy, calibrated questions, accusation audits, mirroring |

### Utility

| Skill | What it does |
|-------|-------------|
| `i-am-sam` | Routes general questions to the right skill |
| `episode-recommender` | Find episodes by topic or guest |

## What's in the repo

```
i-am-sam/
├── .claude-plugin/plugin.json
├── CLAUDE.md                          # Plugin context (Claude reads this)
├── INSTALL.md
├── skills/                            # 18 skill definitions
│   ├── i-am-sam/SKILL.md             # Router
│   ├── idea-vetter/SKILL.md
│   ├── gauntlet/SKILL.md
│   ├── people-intel/SKILL.md
│   └── ...
└── references/
    ├── frameworks/                    # 134 framework articles
    ├── people/                        # 38 people profiles
    ├── entities/                      # Entity intelligence (co-occurrence, sentiment)
    ├── indexes/                       # by-framework, by-guest, by-topic
    └── transcripts/
        ├── mfm/                       # 690 polished MFM transcripts
        └── moneywise/                 # 83 MoneyWise transcripts
```

## How it works

Three layers. Skills are interactive — they ask about your situation and apply frameworks step by step. Framework articles are the 134 written guides (PE rollups, zero-dollar acquisitions, tactical empathy, emotional home framework, etc.) with source quotes. Transcripts are the raw archive, searchable for any question the articles don't cover.

Skills pull from articles when they need depth. Articles cite specific transcripts. Everything traces back to a real episode.

## Credits

Source material: [My First Million](https://www.youtube.com/c/MyFirstMillionPod) by Sam Parr & Shaan Puri, and [MoneyWise](https://www.youtube.com/@moneywise) by Sam Parr.

Built by [Creative Intelligence Agency](https://creativeintel.agency).

Not affiliated with Sam Parr, Shaan Puri, or Hampton. This is an editorial reorganization of publicly available podcast content.
