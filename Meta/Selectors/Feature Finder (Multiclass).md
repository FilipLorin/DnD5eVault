---
wizard-level: 3
---

```dataview
TABLE WITHOUT ID file.link AS "Feature", level, link(class) AS class, link(subclass) as subclass
	FROM "Rules/Modules/Class Features"
	SORT number(level) ASC
	WHERE default(artificer-level, 21) <= this.artificer-level
	WHERE default(barbarian-level, 21) <= this.barbarian-level
	WHERE default(bard-level, 21) <= this.bard-level
	WHERE default(cleric-level, 21) <= this.cleric-level
	WHERE default(druid-level, 21) <= this.druid-level
	WHERE default(fighter-level, 21) <= this.fighter-level
	WHERE default(monk-level, 21) <= this.monk-level
	WHERE default(paladin-level, 21) <= this.paladin-level
	WHERE default(ranger-level, 21) <= this.ranger-level
	WHERE default(rogue-level, 21) <= this.rogue-level
	WHERE default(sorcerer-level, 21) <= this.sorcerer-level
	WHERE default(warlock-level, 21) <= this.warlock-level
	WHERE wizard-level <= this.wizard-level
```


