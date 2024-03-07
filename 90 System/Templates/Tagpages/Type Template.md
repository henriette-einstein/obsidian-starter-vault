---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: <% tp.date.now() %>
key: 
aliases:
---
# [[Types]] > [[<% tp.file.title %>]]
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
