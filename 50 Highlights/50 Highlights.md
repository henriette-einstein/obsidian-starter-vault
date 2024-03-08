---
up: "[[Home]]"
tags:
  - Type/Tagpage
created: 2024-03-06
key: Highlights
aliases:
  - "#Highlights"
cssclasses:
  - banner-image
  - cards-cover
  - cards
banner: "[[Highlights.webp]]"
label: Highlights
description: Highlights on books, articles etc.
---
> [!banner-image] ![[Highlights.webp|py-70]]
# [[Home]] > [[50 Highlights|Highlights]] 
```dataview
table without id embed(banner) as "Banner", "**" + link(file.link, label)+ "**" as "Name" from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```

## Uncategorized Highlights
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
