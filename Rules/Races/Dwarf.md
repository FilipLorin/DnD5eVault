---
race: "[[Rules/Races/Dwarf.md|Dwarf]]"
subrace: "[[Rules/Modules/Subraces/Hill Dwarf.md|Hill Dwarf]]"
source: PHB
---
_Kingdoms rich in ancient grandeur, halls carved into the roots of mountains, the echoing of picks and hammers in deep mines and blazing forges, a commitment to clan and tradition, and a burning hatred of goblins and orcs – these common threads unite all dwarves._

Ability score increase: +2 #Constitution
Languages: #common, #dwarvish
Speed: 25 feet (7.5 m), not reduced by wearing [[heavy armour]]
Size: Medium

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


