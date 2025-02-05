---
draft: false
title: main page
---
```dataview
TABLE WITHOUT ID file.etags
FROM "content/notes"
WHERE file.etags
FLATTEN file.etags AS tag
GROUP BY tag
FLATTEN rows.tag AS unique
GROUP BY true
```


You will find here short notes on various topics, e.g. #management 

Every note has a [[Disclaimer|Disclaimer]]