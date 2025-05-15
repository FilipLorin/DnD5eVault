---
level: "10"
class: Barbarian
---

```dataview
LIST 
	FROM "Rules/Modules/Class Features"
	WHERE file.level <= level
	AND file.class = class
	SORT file.level ASC
```
