---
obsidianUIMode: preview
---
```meta-bind-button
label: New NPC
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateNPC.md"
    fileName: NewNPC
```

```dataview
TABLE WITHOUT ID link(file.name) AS "NPC Name",chapter,Location AS "Location", Alignment AS "Alignment", Character-Role as "Role",associatedGroup AS "Group" , vitality AS "Status"
from "3-Compendium/NPCs"
sort chapter ASC
where NoteIcon = "npc"
```


