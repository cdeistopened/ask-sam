# Installing I Am Sam

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/cdeistopened/i-am-sam.git
```

Put it wherever you keep plugins. Common locations:
- `~/.claude/plugins/i-am-sam`
- `~/plugins/i-am-sam`
- Anywhere — just note the path

### 2. Add to Claude Code

Add the plugin path to your settings. For global access (available in every project), edit `~/.claude/settings.json`:

```json
{
  "plugins": [
    "/absolute/path/to/i-am-sam"
  ]
}
```

For project-specific access, add it to your project's `.claude/settings.json` instead.

### 3. Restart Claude Code

Plugins load on startup. After editing settings, restart your session for the skills to appear.

### 4. Verify

```
/i-am-sam
```

You should see the router respond. If it says the skill isn't found, check that the path in your settings.json is correct and absolute.

## Optional: Index with QMD

If you have [QMD](https://github.com/cdeistopened/qmd) installed, you can index the transcripts for semantic search. This makes cross-archive questions significantly more accurate — instead of grep, Claude can do vector similarity search across all 773 episodes.

Add to your `~/.config/qmd/index.yml`:

```yaml
i-am-sam-mfm:
  path: /path/to/i-am-sam/references/transcripts/mfm
  glob: "**/*.md"

i-am-sam-moneywise:
  path: /path/to/i-am-sam/references/transcripts/moneywise
  glob: "**/*.md"
```

Then:

```bash
qmd reindex i-am-sam-mfm i-am-sam-moneywise
qmd embed i-am-sam-mfm i-am-sam-moneywise
```

The plugin works without QMD — it uses framework indexes and grep. QMD just makes retrieval better for open-ended questions that span many episodes.

## First Questions to Try

**Run the gauntlet** (5-stage business evaluation):
```
I want to start a premium dog food subscription box. Run the gauntlet.
```

**People intelligence:**
```
Build me a dossier on Alex Hormozi — every episode, key quotes, who he's connected to.
```

**Decision skill:**
```
I'm thinking about buying a laundromat chain for $1.2M — is it a good deal?
```

**Content mining:**
```
What topics have been discussed across many episodes but never got a dedicated deep dive?
```

## Troubleshooting

- **Skills not found:** Check the path in `settings.json` is absolute (starts with `/`). Restart Claude Code after editing.
- **Generic answers:** Invoke a skill directly — e.g., `/i-am-sam:idea-vetter` — to use the structured framework path instead of open-ended chat.
- **Old prefix:** If you had the previous version, update `/ask-sam:` to `/i-am-sam:` in any saved prompts.

## Learn More

[creativeintel.agency](https://creativeintel.agency)
