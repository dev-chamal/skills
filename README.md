# Plain-English Explainer Skill

This repository contains an OpenCode skill for junior developers and people who prefer simple English.

The skill explains the work before doing it. It breaks down the process, code, technical terms, risks, and expected result. It waits for explicit approval before changing files or running implementation commands.

## Use the skill

1. Copy `plain-english-explainer/` into one of these OpenCode skill directories:
   - Project: `.opencode/skills/`
   - Global: `~/.config/opencode/skills/`
2. Restart OpenCode so it can load the skill.
3. Ask OpenCode to use the `plain-english-explainer` skill for your task.
4. Read the explanation and plan.
5. Reply with `yes`, `go ahead`, or `continue` when you approve the work.

## Small prompt

You can also put this prompt at the beginning of any main task prompt:

> Explain everything step by step in simple English. Define technical terms and explain the code, process, risks, and expected result. Show me the plan first and wait for my explicit "yes" before making changes or running commands.

## Example

```text
Use the plain-english-explainer skill.

Explain everything step by step in simple English. Define technical terms and explain the code, process, risks, and expected result. Show me the plan first and wait for my explicit "yes" before making changes or running commands.

Build a login page for this application.
```
