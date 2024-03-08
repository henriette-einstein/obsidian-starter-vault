---
up: "[[Categories]]"
tags:
  - Type/Tagpage
label: "{{title}}"
description: 
created: "{{date}}"
key: 
aliases:
---
# [[Categories]] > [[{{title}}]]
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
