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
		AND (barbarian-subclass = this.barbarian-subclass
			OR barbarian-subclass = null))
	OR (default(bard-level, 21) <= this.bard-level
		AND (bard-subclass = this.bard-subclass
			OR bard-subclass = null))
	OR (default(cleric-level, 21) <= this.cleric-level
		AND (cleric-subclass = this.cleric-subclass
			OR cleric-subclass = null))
	OR (default(druid-level, 21) <= this.druid-level
		AND (druid-subclass = this.druid-subclass
			OR druid-subclass = null))
	OR (default(fighter-level, 21) <= this.fighter-level
		AND (fighter-subclass = this.fighter-subclass
			OR fighter-subclass = null))
	OR (default(monk-level, 21) <= this.monk-level
		AND (monk-subclass = this.monk-subclass
			OR monk-subclass = null))
	OR (default(paladin-level, 21) <= this.paladin-level
		AND (paladin-subclass = this.paladin-subclass
			OR paladin-subclass = null))
	OR (default(ranger-level, 21) <= this.ranger-level
		AND (ranger-subclass = this.ranger-subclass
			OR ranger-subclass = null))
	OR (default(rogue-level, 21) <= this.rogue-level
		AND (rogue-subclass = this.rogue-subclass
			OR rogue-subclass = null))
	OR (default(sorcerer-level, 21) <= this.sorcerer-level
		AND (sorcerer-subclass = this.sorcerer-subclass
			OR sorcerer-subclass = null))
	OR (default(warlock-level, 21) <= this.warlock-level
		AND (warlock-subclass = this.warlock-subclass
			OR warlock-subclass = null))
	OR (default(wizard-level, 21) <= this.wizard-level
		AND (wizard-subclass = this.wizard-subclass
			OR wizard-subclass = null))
```




