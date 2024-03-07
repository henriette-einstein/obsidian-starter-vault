---
up: 
tags:
  - Type/MOC
created: 2024-03-07
label: Recently imported highlights
description: Highlights imported from Readwise the last few day
aliases:
  - Recently imported Highlights
---
# [[Recently imported Highlights]]

```dataview
table "[[" + dateformat(file.cday,"yyyy-MM-dd") + "]]" as "Created" from !"90 System" and #Highlights WHERE (file.ctime >= date(today) - dur(10 day))
sort file.ctime
```
# See also
- [[Recent Notes|Recently created notes]]