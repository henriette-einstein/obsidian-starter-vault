---
up: "[[50 Highlights]]"
label: Articles
description: Highlights on articles
tags:
  - Type/Tagpage
  - Category/System
created: 2024-03-06
aliases:
  - "#Highlights/Article"
cssclasses:
  - banner-image
banner: "[[Article Highlights.webp]]"
---
> [!banner-image] ![[Article Highlights.webp|py-80]]
# [[50 Highlights|Highlights]] > [[Article Highlights|Article Highlights]]
## Notes
```dataview
list from !"90 System"
where econtains(file.etags, this.aliases[0])
sort file.name
```
