---
obsidianUIMode: preview
---
```meta-bind-button
label: New Item
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateMagicItem.md"
    fileName: NewMagicItem
```

```dataview
TABLE WITHOUT ID link(file.name) AS "Item Name",SourceType as "Type",Rarity,Importance,Location AS "Location",currentOwner as "Owner",itemImportance as "Importance"
from "3-Compendium/Items"
sort chapter ASC
where NoteIcon = "magicitem"
```
^abyssal-seeds-overview