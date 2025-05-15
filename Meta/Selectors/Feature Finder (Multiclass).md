---
wizard-level: 3
rogue-level: 2
---

```dataview
TABLE WITHOUT ID file.link AS "Feature", level, link(class) AS class, link(subclass) as subclass
	FROM "Rules/Modules/Class Features"
	SORT number(level) ASC
	WHERE default(artificer-level, 21) <= this.artificer-level
	OR (default(barbarian-level, 21) <= this.barbarian-level
		AND barbarian-subclass = this.barbarian-subclass)
	OR default(bard-level, 21) <= this.bard-level
	OR (default(cleric-level, 21) <= this.cleric-level
		AND cleric-subclass = this.cleric-subclass)
	OR default(druid-level, 21) <= this.druid-level
	OR default(fighter-level, 21) <= this.fighter-level
	OR default(monk-level, 21) <= this.monk-level
	OR default(paladin-level, 21) <= this.paladin-level
	OR default(ranger-level, 21) <= this.ranger-level
	OR default(rogue-level, 21) <= this.rogue-level
	OR default(sorcerer-level, 21) <= this.sorcerer-level
	OR default(warlock-level, 21) <= this.warlock-level
	OR default(wizard-level, 21) <= this.wizard-level
```


