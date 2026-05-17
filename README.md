# Writing Editor Skill for Claude Code

A Claude Code skill for editing and polishing written pieces using Volpe's structured method — from rough draft to publish-ready, with the author in control of every change.

## What it does

This skill guides Claude through a 10-step editing workflow:

1. Confirm the draft is complete before starting
2. Identify the audience and publication venue
3. Fix placeholders (sources, footnotes, TODOs)
4. Hunt for sources to back each claim
5. Apply inline linking (no bare "source" text)
6. Fix errors — typos, grammar, punctuation — one paragraph at a time
7. Review formatting and spacing
8. Structured review of opener, structure, and claims
9. Polish phrasing and split long paragraphs
10. Translate if needed, with cross-linked bilingual versions

The author approves every change before it's applied.

## Installation

Place `writing-editor.md` in your Claude Code skills directory:

```bash
# macOS / Linux
cp writing-editor.md ~/.claude/skills/

# Or use curl
curl -o ~/.claude/skills/writing-editor.md \
  https://raw.githubusercontent.com/martinvol/writing-editor-skill/main/writing-editor.md
```

## Usage

In Claude Code, type:

```
/writing-editor
```

Then paste or describe your draft. Claude will follow the structured workflow, asking for your approval at each step.

## Author

Created by [Martín Volpe](https://martinvol.pe/blog) — used for editing posts on his personal blog.
