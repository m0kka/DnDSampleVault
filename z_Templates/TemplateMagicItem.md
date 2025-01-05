---
obsidianUIMode: preview
cssclasses:
  - json5e-item
tags:
  - item
aliases: 
Rarity: common
SourceType: Wondrous Item
NoteIcon: magicitem
BookSource: 
itemImportance: 
currentOwner: 
previousOwner: 
Location:
---

<% await tp.file.move("/3-Compendium/Items/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewMagicItem");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Item Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


# `=this.file.name`
*`=this.SourceType`, `=this.rarity` (requires attunement by a druid or ranger)*.

- **Damage**: 1d4 S
- **Properties**: [Light](/3-Compendium/CLI/rules/item-properties.md#Light), Requires Attunement
- **Cost**: ⏤
- **Weight**: 2.0 lbs.

Description

*Source: `=this.BookSource`*