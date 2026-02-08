Automating my planning one AI assistant at a time.

## Purpose

This repository serves as a **lightweight planning dashboard** across all my projects and initiatives. It's not a task tracker or issue manager—it's a single place to answer: "What am I working on?" and "What should I do next?"

## Philosophy

### Keep It Light
- Store **metadata** (titles, descriptions, phase, state, dates)
- Store **links** to canonical sources (GitHub repos, issue trackers, deployment URLs)
- Store **next 3-5 actions** for each project—just enough to resume work without context switching
- Store **current focus and ephemeral notes** that help me pick up where I left off

### Keep The Source of Truth Elsewhere
- **Full task backlogs** live in project repos or issue trackers (GitHub Issues, Linear, etc.)
- **Detailed specs and requirements** live with the code
- **Historical decisions and long-term reference** live where teams can access them
- **Collaboration** happens in shared tools, not in my personal planning repo

### The Workflow
1. **Planning time**: Scan this repo to see all projects + immediate next actions
2. **Working time**: Jump from here to the canonical source (GitHub issues, project docs) for full context
3. **Syncing**: Periodically update the "next actions" here based on progress in the canonical tracker

This approach prevents data duplication while maintaining a fast, scannable view of everything in motion.

## Task Management Strategy

Tasks can live in three places:

1. **This planning repo** (`## Tasks` in project files): Next 3-5 actions during early brainstorming or when a project doesn't yet have dedicated infrastructure
2. **Project repositories**: Issues, docs, or task lists in the codebase itself
3. **External trackers**: GitHub Issues, Linear, Notion, etc.

As projects mature, tasks typically migrate from (1) → (2) or (3). The `tracker:` field in project frontmatter points to the canonical source. If a `github:` field exists and no `tracker:` is specified, assume issues live at `{github}/issues`.
