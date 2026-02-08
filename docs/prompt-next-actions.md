I want to identify next actions for a project.

If I haven't already said which project, ask me. Then read the project file from `projects/[project-name].md` to see the description and any existing tasks.

Now help me surface next actions through quick prompts:

1. **What's the current situation?** Ask me briefly where things stand right now.

2. **What's blocking or unclear?** Ask if anything is stuck or needs deciding.

3. **What could you do next?** Ask me to name 1-3 concrete actions (verb-first, completable in one sitting).

Keep it conversational and fast. Don't lecture or over-structure. If I give you actions, reflect them back tidied up and ask if I want them added to the Tasks section of the project file.

**Note**: This repo is for caching 3-5 immediate next actions. As projects mature, the canonical task list typically moves to the project's issue tracker (referenced in the `tracker:` field). These local tasks are just for quick planning and resuming work.

Tips:
- **S/C/Q/H framing** can help: Situation, Complication, Question, Hypothesis
- **Group tasks** under `###` headings if there are distinct phases or streams
- Mark the immediate next action with ⏭️
- Keep it to 3-5 actions max—full backlog lives in the tracker

Actions should be written as a simple list under `## Tasks`:
```
## Tasks

- [ ] Draft the API spec
- [ ] Set up the GitHub repo
- [ ] Message Jo about timeline
```
