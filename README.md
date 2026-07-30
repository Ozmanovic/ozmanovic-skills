# ozmanovic-skills

Practical skills for AI agents, focused on clear writing and useful workflows.

## Install

Recommended interactive install:

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills
```

Choose the skills and agent environments you want when prompted.

### Install options

List the available skills without installing them:

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills --list
```

Install only Jargonless globally for Codex:

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills \
  --skill jargonless-reporting \
  --agent codex \
  --global
```

Install all skills globally for Codex:

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills \
  --skill '*' \
  --agent codex \
  --global \
  --yes
```

Install all skills globally for every detected agent:

```bash
npx skills@latest add Ozmanovic/ozmanovic-skills \
  --all \
  --global
```

Without `--global`, skills are installed for the current project. Use `--global` to make them available across projects.

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

