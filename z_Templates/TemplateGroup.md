---
tags:
  - Category/Group
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
Leader: 
PrimaryHome: 
NoteIcon: group
obsidianUIMode: preview
---

<% await tp.file.move("/3-Compendium/Factions/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewGroup");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Group Name");  
await tp.file.rename(title);  
} else {  
title = tp.file.title;  
}  
_%>

> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png]]
> ###### Key Members
> ```dataview
table Race, Gender
where contains( AssociatedGroup, this.file.link)

# `=this.file.name`
## Overview
...

## Etymology
...
## Activities
...

## Society
### Beliefs
...
### Culture
...

### Religion
...

## Relations
### Allies
...

### Enemies
...

## Possessions
...

## History
...

## Rumors & Legends
...


