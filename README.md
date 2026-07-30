# ozmanovic-skills

Practical skills for AI agents, focused on clear writing and useful workflows.

## Install

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills
```

Choose the skills and agent environments you want when prompted.

## Skills

### Productivity

- [`jargonless-reporting`](skills/productivity/jargonless-reporting) — Select an action-first, decision-first, or hybrid structure for substantive reports.

### Work skills

Obsidian work-memory skills for preserving and resuming project context:

- [`setup-obsidian-work-skills`](skills/work-skills/setup-obsidian-work-skills) — Configure the vault, repository roots, and agent sources.
- [`save-work-checkpoint`](skills/work-skills/save-work-checkpoint) — Save the current state of work in progress.
- [`resume-project-context`](skills/work-skills/resume-project-context) — Resume from the latest reliable project context.
- [`project-completed-summary`](skills/work-skills/project-completed-summary) — Save a durable summary of completed work.
- [`retro-summary`](skills/work-skills/retro-summary) — Recover summaries for older work from agent sessions and repositories.
- [`implementation-finder`](skills/work-skills/implementation-finder) — Find comparable local implementations before making changes.
- [`project-autojournal`](skills/work-skills/project-autojournal) — Create project-memory checkpoints from recent agent work.

The complete Obsidian package, including its installer, diagnostics, and optional scheduled-autojournal scripts, remains available in [`Ozmanovic/obsidian-work-skills`](https://github.com/Ozmanovic/obsidian-work-skills).

## Repository structure

Skills are grouped by purpose, with one self-contained directory per skill:

```text
skills/
├── productivity/
│   └── <skill-name>/
└── work-skills/
    └── <skill-name>/
```
