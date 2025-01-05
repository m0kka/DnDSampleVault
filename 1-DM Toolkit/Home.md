---
obsidianUIMode: preview
---

![[ToDo-List]]

<br>

> [!cards|4]
> **[[Link]]**
> [![[Northern Faerun Map.jpg\|sban htiny ctr]]](Lampoteuo)
> 
> **[[Journey Board]]**
> [![[JourneyBoard.png\|sban htiny ctr]]](Journey%20Board.md)
>
> **[[0-Introduction|Chapter 0: Introduction]]**
> [![[AdventureIcon.png\|sban htiny ctr]]](0-Introduction)
> 
> **[[The World Weary]]**
> [![[PartyLogo.jpg\|sban htiny ctr p+t]]](The%20World%20Weary)


> [!infobox]
> # Session Journals
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Session Date", Status, players
from "1-Session Journals"
where (type = "Session Journal")
SORT file.name DESC

```dataview  
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race  
from "1-Party"  
where (Role = "Player")  
where (Status = "Active")  
```

# Calendar
```calendarium
```

# Recently Modified NPCs

```dataview  
TABLE WITHOUT ID link(file.name) AS "NPC Name", Gender, Race, Age, Location, AssociatedGroup  
FROM "3-Compendium/NPCs"
WHERE (NoteIcon = "npc") 
SORT file.mtime DESC
LIMIT 10
```

# Recently Modified Locations

```dataview  
TABLE WITHOUT ID link(file.name) AS "Location Name", type, Government, Community-Size, size, population  
FROM "2-World"
WHERE (NoteIcon = "Settlement")  
SORT file.mtime DESC
LIMIT 10
```


# Recently Modified Notes
```dataview
TABLE WITHOUT ID
    link(file.path, file.folder + " / " + file.name) AS "Note",
    file.mtime AS "Last modified"
FROM "/"
WHERE file.mtime >= date(today) - dur(30 days)
AND file.name != this.file.name
    AND !contains(file.path, "z_Assets")
    AND !contains(file.path, "Inline Scripts")
    AND !contains(file.path, "z_Templates")
    AND !contains(file.path, "daily notes")
    AND !contains(file.path, "BRAT")
SORT file.mtime DESC
LIMIT 10
```
