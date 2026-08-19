---
publish: true
permalink: /People Notes/Matt Negri.md
created: 2026-08-19T17:26:28.424Z
modified: 2026-08-19T17:26:39.210Z
published: 2026-08-19T17:26:39.210Z
tags:
  - person
type: person
role:
---

# Matt Negri

## Open Action Items

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
