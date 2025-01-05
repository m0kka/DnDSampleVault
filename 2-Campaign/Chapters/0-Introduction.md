---
obsidianUIMode: preview
tags:
  - chapter
---

# Chapter 0: Introduction
## Summary


## Chapter Quests
```dataview
TABLE WITHOUT ID link(file.name) AS "Quest Name", questStatus AS "Status", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Rewards", questImportance AS "Importance"
from "2-Campaign" AND #quest
where contains(questChapter, this.file.link)
```


## Chapter Sessions
```dataview
TABLE WITHOUT ID link(file.name) AS "Session Date", Status, players
from "1-Session Journals"
where (type = "Session Journal") AND (contains(chapter, this.file.link))
SORT file.name DESC
```


## Chapter NPCs
```dataview
TABLE WITHOUT ID link(file.name) AS "NPC Name",Location AS "Location", Alignment AS "Alignment", Character-Role as "Role",associatedGroup AS "Group" , vitality AS "Status"
from "3-Compendium/NPCs"
sort vitality ASC
where (NoteIcon = "npc") AND (contains(chapter,this.file.link))
```
