---
up: "[[Types]]"
tags:
  - Type/Tagpage
label:
  "{{title}}"
description: 
created: "{{date}}"
key: 
aliases:
---
# [[Types]] > [[{{title}}]]
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
