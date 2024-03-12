---
up: "[[20 Tags]]"
tags:
  - Type/Tagpage
  - Category/System
label: System
description: Templates and other configuration items
created: 2024-03-05
aliases:
  - "#Category"
cssclasses:
  - banner-image
---
> [!banner-image] ![[Categories.webp]]
# [[20 Tags|Discovery]] > [[Categories]]
## Notes
```dataview
table description from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```

## Notes
```dataview
list from !"90 System"
where econtains(file.etags, this.aliases[0])
sort file.name
```
