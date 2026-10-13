# Eghed Skills

Practical, editable skills for AI agents, built by [Eghed](https://github.com/eghed) for data scientists and data engineers.

A skill is a short markdown file (`SKILL.md`) that tells an AI agent how to do one kind of task well: what to focus on, the steps to follow, and what to avoid. Skills are plain text, so you can read them, change them and share them.

## Skills

| Skill | What it does |
|---|---|
| [cv-professional-summary](skills/career/cv-professional-summary/SKILL.md) | Writes a third-person CV summary, tailored to a job description, that grabs a recruiter's attention and sells the candidate. |

More skills for data science and data engineering will be added here.

## Use a skill

Each skill lives in its own folder under `skills/<category>/<skill-name>/`.

**Claude Code:** copy the skill's folder into `~/.claude/skills/` (for all projects) or `.claude/skills/` inside a project (for that project only). The agent picks it up when a task matches the skill's `description`.

**Other agents:** most agents that support `SKILL.md` files can read the same folder. Check your agent's documentation for where skills go.

Copied skills do not update themselves. Pull this repo again when you want the latest version.

## Repo layout

```
skills/
└── <category>/
    └── <skill-name>/
        └── SKILL.md
```

Categories group related skills (for example `career`). Each skill gets its own folder so it can later hold extra files next to its `SKILL.md`.

## Contribute

Found a way to make a skill better, or have a new one to share? See [CONTRIBUTING.md](CONTRIBUTING.md). The quickest route is to open a skill on GitHub, click the pencil icon, and propose your change as a pull request.

## License

[MIT](LICENSE)
