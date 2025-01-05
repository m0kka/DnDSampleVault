---
obsidianUIMode: preview
---

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level
from "1-Party"
where (Role = "Player") 
where (Status = "Active") 
```

<br> %% this forces a break line into the note %%
# The Graveyard

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level, Status
from "1-Party"
where (Role = "Player") 
where (Status != "Active") 
```

