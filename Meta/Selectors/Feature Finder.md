---
level: "1"
class: Barbarian
---

```dataview
LIST 
	FROM "Rules/Modules/Class Features"
	WHERE level <= file.level
	AND class = file.class
	AND barbarian-level <= file.barbarian-level
```
