```dataview
TABLE WITHOUT ID file.link AS "Feature", level, class, subclass
	FROM "Rules/Modules/Class Features"
	SORT number(level) ASC
	WHERE level <= this.level
	WHERE class = this.class
```
