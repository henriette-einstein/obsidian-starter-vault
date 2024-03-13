---
up: 
tags:
  - Type/MOC
label: Best Connected Notes
description: Notes with the most incoming and outgoing links
created: 2024-03-13
---
# [[Best Connected Notes]]


> [!NOTE]+ Thanks
> This query is described by PKM Explorer. Please read
> [Surfacing the most relevant notes in your Obsidian vault](https://medium.com/@PKMExplorer/surfacing-the-most-relevant-notes-in-your-obsidian-vault-bb0bb88fdd25)
> for further information
> Thanks!


```dataview
table 
length(file.outlinks) as "Outgoing",
length(file.inlinks) as "Incoming",
length(file.outlinks) + length(file.inlinks) as "Total Links"
sort length(file.outlinks) + length(file.inlinks) DESC
limit 20
```
