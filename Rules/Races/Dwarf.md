---
race: "[[Rules/Races/Dwarf.md|Dwarf]]"
subrace: "[[Rules/Modules/Subraces/Hill Dwarf.md|Hill Dwarf]]"
source: PHB
---
Ability score increase: +2 #Constitution
Languages: #common, #dwarvish
Speed:
Size:

## Features:
- [[Dwarven Resilience]]
- [[Dwarven Combat Training]]
- [[Darkvision]]
- [[Stonecunning]]
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


