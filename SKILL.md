---
name: Writing Editor
description: A structured writing editing skill for Claude Code that guides you from rough draft to publish-ready, with the author in control of every change.
author: Martín Volpe
author_url: https://martinvol.pe/
license: GPL-3.0
---

# Writing Editor

A structured writing editing skill for Claude Code that guides you from rough draft to publish-ready, with the author in control of every change.

## Description

This skill implements Volpe's 10-step editing method: source hunting, inline linking, error fixing, structured review, polish, and optional translation. Claude handles research and mechanical fixes while the author approves every editorial decision.

## Usage

Install the skill file:

```bash
cp skills/writing-editor.md ~/.claude/skills/
```

Or with curl:

```bash
curl -o ~/.claude/skills/writing-editor.md \
  https://raw.githubusercontent.com/martinvol/writing-editor-skill/main/skills/writing-editor.md
```

Then invoke it in Claude Code:

```
/writing-editor
```

Paste your draft when prompted. The skill will walk you through each step and ask for your approval before applying any change.

## Requirements

- [Claude Code](https://claude.ai/code)
- A complete draft ready for editing (the skill refuses to work from vague ideas)

## Author

Created by [Martín Volpe](https://martinvol.pe/)
