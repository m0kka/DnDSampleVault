---
obsidianUIMode: preview
---

`BUTTON[button_quest]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest Name", questStatus AS "Status", questChapter AS "Chapter", questImportance AS "Importance", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Rewards"
from "2-Campaign" AND #quest
SORT questChapter ASC
where questStatus != "Hidden"
```
