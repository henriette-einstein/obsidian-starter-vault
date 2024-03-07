---
tags:
  - Type/Note
created: 2024-03-07
aliases:
  - Untyped Notes
label: Untyped Notes
description: Notes with no tags attached
---
# [[Untyped Notes]]

```dataview
table "[[" + dateformat(file.cday,"yyyy-MM-dd") + "]]" as "Created" from !"90 System" and !#Type
sort file.ctime
```

# See also
- [[Recent Notes|Recently created notes]]
