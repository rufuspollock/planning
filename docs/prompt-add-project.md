I want to add a new project to my projects catalog.

First, ask me to describe the project. I'll provide a rough description.

Then generate:
1. **Title**: Concise project name (2-5 words)
2. **Short description**: One sentence under 120 characters
3. **Full description**: Tidy 2-4 sentence description

Present these and ask if I'd like any tweaks. If I ask for title options, provide 3 alternatives.

Once approved, write the project file to `projects/[kebab-case-title].md` using this format:

```
---
title: [Title]
description: [Short description]
created: [today's date YYYY-MM-DD]
---

[Full description]

## Tasks
```
