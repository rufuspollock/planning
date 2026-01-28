I want to add a new project to my projects catalog.

First, ask me to describe the project. I'll provide a rough description.

Then generate:
1. **Title**: Concise project name (2-5 words)
2. **Short description**: One sentence under 120 characters
3. **Full description**: Tidy 2-4 sentence description

Present these and ask if I'd like any tweaks. If I ask for title options, provide 3 alternatives.

Once I approve the description, quickly ask me these optional fields one by one (I can skip any):
- **GitHub URL?** (stored as `github`)
- **Homepage URL?** (stored as `url`)
- **Phase?** (inbox, shaping, shipping, sharing)
- **State?** (backlog, in progress, done, paused)

Then write the project file to `projects/[kebab-case-title].md` using this format:

```
---
title: [Title]
description: [Short description]
created: [today's date YYYY-MM-DD]
github: [if provided]
url: [if provided]
phase: [if provided]
state: [if provided]
---

[Full description]

## Tasks
```

Omit any frontmatter fields that weren't provided.
