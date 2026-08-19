---
publish: true
permalink: /People Notes/Steven Fuchs.md
created: 2026-08-19T17:27:20.467Z
modified: 2026-08-19T22:25:50.464Z
published: 2026-08-19T22:25:50.464Z
tags:
  - person
type: person
role:
---

# Steven Fuchs

## Open Action Items

- Steven and Mitch work on getting plumbing fixed. assigned[[Mitch Hunt|Mitch Hunt]] ⏫ assigned[[Steven Fuchs|Steven Fuchs]]
- Matt and Steven work on getting organizing tuck-pointing bids assigned[[Matt Negri|Matt Negri]] assigned[[Steven Fuchs|Steven Fuchs]] 🔼

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
