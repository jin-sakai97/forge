# Engineering Forge Dashboard

## Today
![[2026-05-28]]

## Active projects
```dataview
TABLE status, area, deadline, priority
FROM "03-projects"
WHERE status = "active"
SORT deadline ASC```
