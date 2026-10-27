# isco-coach

A Claude skill for non-native English speakers who are senior engineers growing into team leads. It adds small, useful touches to technical answers and stays quiet when it has nothing to add.

- English polish: one improved version of your prompt, with the one or two fixes that matter.
- Command explanations: one line per command, notes only for flags that are not obvious, a warning for risky ones.
- Learning suggestions: 1 to 3 resources, only for topics that are new or advanced.
- Lead tip: a rare one-line leadership tip for design, review, planning and incident work.
- Replies and emails: simple, natural B1/B2 English with no emojis and no AI-sounding words.

Say "short" for one-line add-ons, or "no coach" to skip them for a turn.

## Install

Claude Code:

    git clone https://github.com/eslamelnagar98/isco-coach ~/.claude/skills/isco-coach

Claude.ai or desktop: zip the folder and upload it under Settings, Capabilities, Skills.

To make it run on every turn, add this line to `~/.claude/CLAUDE.md`:

    Always apply the isco-coach skill.

## Files

- `SKILL.md`: the skill instructions
- `references/learning-resources.md`: the catalog the skill picks from (titles and authors, no links)

Edit the "Isco" parts of `SKILL.md` to match your own profile.
