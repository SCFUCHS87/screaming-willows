---
publish: true
permalink: /People Notes/Phil Lamczyk.md
created: 2026-08-19T17:25:57.915Z
modified: 2026-08-19T17:26:28.421Z
published: 2026-08-19T17:26:28.421Z
tags:
  - person
type: person
role:
---

# Phil Lamczyk

## Open Action Items

- Phil turn in Park House lease assigned[[Phil Lamczyk|Phil Lamczyk]] ⏫

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
