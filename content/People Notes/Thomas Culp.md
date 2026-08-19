---
publish: true
permalink: /People Notes/Thomas Culp.md
created: 2026-08-19T17:26:49.557Z
modified: 2026-08-19T17:26:59.354Z
published: 2026-08-19T17:26:59.354Z
tags:
  - person
type: person
role:
---

# Thomas Culp

## Open Action Items

- Thomas work on park house painting and dry wall bids assigned[[Thomas Culp|Thomas Culp]] 🔼

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
