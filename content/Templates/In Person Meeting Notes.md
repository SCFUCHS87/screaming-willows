---
publish: true
permalink: /Templates/In Person Meeting Notes.md
created:
  "{ date:YYYY-MM-DD }":
modified: 2026-08-21T03:59:17.208Z
published:
  "{ date:YYYY-MM-DD }":
tags:
  - meetings
date:
  "{ date:YYYY-MM-DD }":
time:
  "{ time:HH:mm }":
type: meeting
attendees:
project:
status: active
---

<%\*
let attendeesInput = await tp.system.prompt("Attendees (comma-separated names)");
let attendeesList = attendeesInput.split(",").map(name => `"[[${name.trim()}]]"`).join("\n  - ");
-%>
---

attendees:

- <% attendeesList %>

---

# {{title}}

## Attendees

-

## Agenda

-

## Notes

## Decisions

-

## Action Items

- \[ ]

## Follow-ups / Open Questions

-

## Related

-
