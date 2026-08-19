---
publish: true
permalink: /People Notes/Linda Weiner.md
created: 2026-08-19T17:26:39.218Z
modified: 2026-08-19T17:26:49.555Z
published: 2026-08-19T17:26:49.555Z
tags:
  - person
type: person
role:
---

# Linda Weiner

## Open Action Items

- Linda work on pocket park beautification and sprucing up. assigned[[Linda Weiner|Linda Weiner]] 🔼
- Linda evaluate plantings at park house assigned[[Linda Weiner|Linda Weiner]] 🔽

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
