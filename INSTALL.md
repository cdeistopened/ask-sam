# Installing I Am Sam

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and working

## Installation

```bash
claude plugin add cdeistopened/i-am-sam
```

## First Questions to Try

**Test the gauntlet** (sequential evaluator):
```
I want to start a premium dog food subscription box. Run the gauntlet.
```
This runs your idea through all 5 stages — Idea Check, Market Sizing, Pricing, Team, Exit — each stage-gated so you see where it passes and where it breaks.

**Test people intelligence**:
```
What does Sam actually think about Alex Hormozi? Give me the full picture.
```
This pulls episode appearances, co-occurrence data, sentiment analysis, and direct quotes — not a generic bio.

**Test a decision skill**:
```
I'm thinking about buying a laundromat chain for $1.2M — is it a good deal?
```
Routes to the acquisition evaluator with frameworks from Wilkinson, Beshore, and Moore.

## Other Good Starting Questions

- "How should I price my SaaS product?"
- "Help me prepare for a salary negotiation"
- "I just sold my company and feel lost — what now?"
- "How should I deploy $500K in capital?"
- "Find me episodes about bootstrapping vs raising money"
- "What gaps exist in the MFM content library?"

## Troubleshooting

- **Skills not showing:** Make sure Claude Code has been restarted after installing the plugin. Run `claude plugin list` to verify it appears.
- **Generic answers instead of Sam-specific:** Invoke a skill directly — e.g., `/i-am-sam:idea-vetter` — to force the structured framework path instead of open-ended chat.
- **Transcripts not found:** The plugin references data in relative paths. Ensure the full plugin directory is intact after installation.
- **"I don't have access to that skill":** Check that you're using the `/i-am-sam:` prefix, not the old `/ask-sam:` prefix.

## Learn More

Visit [creativeintel.agency](https://creativeintel.agency) for more Ask [Creator] plugins.
