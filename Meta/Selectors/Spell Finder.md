---
class: Cleric
level: 1
---


```dataview
TABLE WITHOUT ID file.link AS "Feature", level, casting-time, components
	FROM "Rules/Spells"
	SORT number(level) ASC
	WHERE level <= this.level
	WHERE class = this.class
```
