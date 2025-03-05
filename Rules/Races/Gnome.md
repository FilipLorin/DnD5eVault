---
race: "[[Rules/Races/Gnome.md|Gnome]]"
source: PHB
---
Ability score increase: +2 #Inteligence
Languages: #common, #gnomish
Speed:
Size:

## Features:
- [[Darkvision]]
- [[Gnome Cunning]]

## Subrace
```dataview
LIST
FROM "Rules/Modules/Subraces"
WHERE race=this.race
SORT file.name ASC
```

```meta-bind
INPUT[suggester(optionQuery("Rules/Modules/Subraces")):subrace]
```

 