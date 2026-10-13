# Contributing

Thanks for helping improve these skills. Changes are made through pull requests.

## Edit an existing skill

1. Open the skill's `SKILL.md` on GitHub and click the pencil icon.
2. Make your change.
3. Choose **Create a new branch and start a pull request**, and describe what you changed and why.

Say what output was wrong and how your change fixes it. A before-and-after example is the most useful thing you can add.

## Add a new skill

1. Pick a category folder under `skills/` (create one if none fits).
2. Create `skills/<category>/<skill-name>/SKILL.md`. Use lowercase, hyphenated names, and make the folder name match the `name` in the front matter.
3. Add a row for it to the table in `README.md`.
4. Open a pull request.

## SKILL.md template

```markdown
---
name: skill-name
description: One or two sentences. Say what the skill does and when to use it. This text decides when an agent picks the skill up, so be specific.
---

# Skill Name

One short paragraph on the purpose and who it is for.

## Settings

The knobs people are most likely to change, in a small table. Put them first.

## Process

1. **Step name.** What to do and why.
2. **Step name.** What to do and why.

## Rules

- Hard limits and judgement calls.

## Avoid

- Patterns that make the output worse.

## Examples

Good and bad examples, ideally a before-and-after.

## Check

A short numbered list to confirm before returning the result.
```

## Quality bar

- **Specific description.** A vague description means the skill is never picked up, or is picked up at the wrong time.
- **Explain the why.** Say why a rule exists, so the agent can handle cases the rule did not foresee.
- **Short and focused.** One skill does one job. If it needs two, split it.
- **Examples included.** Real-looking examples teach more than rules do.

## Keep it public-safe

This repo is public. Never include:

- real people's names, CVs or personal data (use fictional examples)
- client names or project details
- credentials, internal URLs or internal prompts
