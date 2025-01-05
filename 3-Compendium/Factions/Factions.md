---
obsidianUIMode: preview
---
```meta-bind-button
label: New Guild or Group
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateGroup.md"
    fileName: NewGroup
```

```dataview
TABLE WITHOUT ID link(file.name) AS "Faction Name",PrimaryHome AS "Location", Alignment AS "Alignment", Leader as "Leader"
from "3-Compendium/Factions"
where NoteIcon = "group"
```
