---
up: "[[Home]]"
tags:
  - Type/Tagpage
created: 2024-03-06
key: Source
aliases:
  - "#Source"
cssclasses:
  - banner-image
  - cards
  - cards-cover
banner: "[[Sources.webp]]"
label: Ressources
description: Notes on books, articles etc.
---
> [!banner-image] ![[Sources.webp]]
# [[40 Sources|Sources]]

## Subtags
```dataview
table without id embed(banner) as "Banner", "**" + link(file.link,label) + "**" as "Name" from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```

## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
