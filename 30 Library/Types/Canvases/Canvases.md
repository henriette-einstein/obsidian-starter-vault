---
up: "[[Types]]"
tags:
  - Type/Tagpage
label: Canvases
description: Canvases in this vault
created: 2024-03-13
aliases:
  - "#Type/Canvas"
---
# [[Types]] > [[Canvases]]
## Canvases
```dataviewjs
const canvas = (app.vault.getFiles()
.filter(file => file.extension === 'canvas')).sort((a, b) => a.name.localeCompare(b.name));; 
dv.list(canvas.map(file => dv.fileLink(file.path)))
```
