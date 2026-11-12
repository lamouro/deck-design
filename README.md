# deck-design

A Claude skill with slide and deck design rules. It loads whenever you ask Claude for slides (Claude Design, PowerPoint, Google Slides or HTML), and makes every deck follow the same rules: one takeaway title per slide, no eyebrow text or subheaders, varied layouts, readable sizes, color that fits the subject, proper use of your assets, and accessibility (alt text, contrast, never color alone).

## Install

**Claude.ai and Claude Design**

1. Download [deck-design.zip](deck-design.zip) from this repo.
2. In Claude, go to Settings > Capabilities > Skills and upload the zip.
3. Ask for a deck. The skill loads on its own.

**Claude Code**

Clone the repo into your skills folder:

```bash
git clone https://github.com/lamouro/deck-design ~/.claude/skills/deck-design
```

Then ask for slides, or type `/deck-design`. Run `git pull` in that folder to get updates.

## What's inside

- `SKILL.md`: the rules
- `references/checklist.md`: the check Claude runs on every slide before handing a deck over
