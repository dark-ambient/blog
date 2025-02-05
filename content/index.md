---
draft: false
title: main page
---

You will find here short notes on various topics, e.g. #management 

```dataview
TABLE WITHOUT ID join(rows.unique, ", ") AS "Tags to ease the navigation"
FROM "content/notes"
WHERE file.etags
FLATTEN file.etags AS tag
GROUP BY tag
FLATTEN rows.tag AS unique
GROUP BY true
```

Every note has a [[Disclaimer|Disclaimer]].