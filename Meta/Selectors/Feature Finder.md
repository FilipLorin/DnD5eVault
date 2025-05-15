---
level: "20"
class: Druid
---

```dataview
TABLE WITHOUT ID link, level, class, subclass
	FROM "Rules/Modules/Class Features"
	SORT number(level) ASC
	WHERE level <= this.level
	WHERE class = this.class
	WITH file.link AS Fea
```

