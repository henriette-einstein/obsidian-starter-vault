---
tags:
  - Type/Note
created: 2024-03-07
aliases:
  - Recently created notes
---
# [[Recent Notes|Recently created notes]]

```dataview
table "[[" + dateformat(file.cday,"yyyy-MM-dd") + "]]" as "Created" from !"90 System" WHERE (file.ctime >= date(today) - dur(10 day))
sort file.ctime
```

# See also
- [[Recent Highlights|Recently imported Highlights]]