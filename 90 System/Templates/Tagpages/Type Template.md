---
up: "[[Types]]"
tags:
  - Type/Tagpage
label: "{{title}}"
description: 
created: "{{date}}"
aliases:
---
# [[Types]] > [[{{title}}]]
## Notes
```dataview
list from !"90 System"
where econtains(file.etags, this.aliases[0])
sort file.name
```
