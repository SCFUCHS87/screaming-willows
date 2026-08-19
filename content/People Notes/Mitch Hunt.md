---
publish: true
permalink: /People Notes/Mitch Hunt.md
created: 2026-08-19T17:13:26.306Z
modified: 2026-08-19T17:13:47.793Z
published: 2026-08-19T17:13:47.793Z
tags:
  - person
type: person
role:
---

# Mitch Hunt

## Open Action Items

- Mitch follow up with park department to find out about waterline assigned[[Mitch Hunt|Mitch Hunt]] ⏫
- Steven and Mitch work on getting plumbing fixed. assigned[[Mitch Hunt|Mitch Hunt]] ⏫ assigned[[Steven Fuchs|Steven Fuchs]]
- Mitch work on sidewalk repairs assigned[[Mitch Hunt|Mitch Hunt]] 🔼

## Completed Action Items

```dataviewjs
const pages = dv.pages('#meeting and -"Templates"');
const tasks = pages.file.tasks.where(t => {
    if (!t.completed || !t.assigned) return false;
    const list = Array.isArray(t.assigned) ? t.assigned : [t.assigned];
    return list.some(a => a.path === dv.current().file.path);
});
dv.taskList(tasks.limit(20), false);
```

## Meetings Attended

- [[Meeting Notes/Maintenace Meeting 08-16-26.md|Maintenace Meeting 08-16-26]]
