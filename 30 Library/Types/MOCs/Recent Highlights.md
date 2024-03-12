---
up: 
tags:
  - Type/MOC
  - Category/System
created: 2024-03-07
label: Recently imported highlights
description: Highlights imported from Readwise the last 5 days
aliases:
  - Recently imported Highlights
---
# [[Recent Highlights|Recently imported Highlights]]

```dataview
table "[[" + dateformat(file.cday,"yyyy-MM-dd") + "]]" as "Created" from !"90 System" and #Highlights WHERE (file.ctime >= date(today) - dur(5 day))
sort file.ctime
```
# See also
- [[Recent Notes|Recently created notes]]
- [[Uncategorized Notes|Uncategorized Notes]]
- [[Untyped Notes|Untyped Notes]]