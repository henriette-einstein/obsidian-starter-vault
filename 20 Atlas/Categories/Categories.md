---
up: "[[20 Atlas]]"
tags:
  - Type/Tagpage
created: 2024-03-05
key: Categories
aliases:
  - "#Categories"
cssclasses:
  - banner-image
---
> [!banner-image] ![[Categories.webp]]
# [[20 Atlas|Atlas]] > [[Categories]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```

## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
