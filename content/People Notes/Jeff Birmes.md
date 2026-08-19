---
publish: true
created: 2026-08-19T17:26:59.356Z
modified: 2026-08-19T22:09:30.816Z
tags:
  - person
---

# Jeff Birmes

## Open Action Items

```dataviewjs
const pages = dv.pages('#meeting and -"Templates"');
const tasks = pages.file.tasks.where(t => {
    if (t.completed || !t.assigned) return false;
    const list = Array.isArray(t.assigned) ? t.assigned : [t.assigned];
    return list.some(a => a.path === dv.current().file.path);
});
dv.taskList(tasks, false);
```

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
