
```dataview
TABLE WITHOUT ID file.link AS "Feature", level, link(class) AS class, link(subclass) as subclass
	FROM "Rules/Modules/Class Features"
	SORT number(level) ASC
	WHERE level <= this.level
	AND class = this.class
```


