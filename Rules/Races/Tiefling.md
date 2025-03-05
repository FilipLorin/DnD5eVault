---
race: "[[Rules/Races/Tiefling.md|Tiefling]]"
source: PHB
---
Ability score increase: +2 #Charisma 
Languages: #common, #infernal
Speed: 30 feet (9 m)
Size: Medium

## Features:
- [[Darkvision]]
- [[Hellish Resistance]]

## Bloodline
```dataview
LIST
FROM "Rules/Modules/Subraces"
WHERE race=this.race
SORT file.name ASC
```

```meta-bind
INPUT[suggester(optionQuery("Rules/Modules/Subraces")):subrace]
```

 
