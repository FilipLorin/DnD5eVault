---
level: "20"
class: Barbarian
---

```dataview
LIST 
	FROM "Rules/Modules/Class Features"
	WHERE level <= this.level
	WHERE class = this.class
	SORT file.level ASC
```
