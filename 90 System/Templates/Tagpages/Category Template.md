---
up: "[[Categories]]"
tags:
  - Type/Tagpage
created: <% tp.date.now() %>
key: 
aliases:
---
# [[Categories]] > [[<% tp.file.title %>]]
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
