DELENDA EST: An overhaul mod for 0 A.D. Empires Ascendant
===========

OVERVIEW
===========
This is an overhaul mod for 0 A.D. Empires Ascendant. Its goal is to introduce a new balance scheme, a revamped and greatly expanded technology tree, and other customizations to the game. The mod endeavors to push the game's modding capability to the fullest and to make the gameplay as enjoyable and as rich as possible.

Keep in mind:
- This mod is incomplete. Not every new planned technology or gameplay change has been implemented yet.
- Many of the planned changes rely upon new features being implemented into the core game or engine.
- This mod can be used to encourage those new features being implemented either by modders, open-source contributors, or official WFG team.

Major unimplemented Features that this document assumes will eventually be implemented:

- Formations: This mod re-enables the old formations from Alpha 16 and before. Once these are reimplemented by the official WFG team, it is planned to revamp them completely for this mod.
- Trample: Some cavalry are planned to be better tramplers than others, so their stats would be adjusted accordingly. So, until Trample is implemented by the team or by modders some Cavalry stats may be wonky.
- Charging/Charge Bonus: Like Trample, this would affect Cavalry stats immensely, and it is hoped that this is eventually implemented in the game.
- Mercenary Camps: This mod starts the process of making Mercenaries a unique class of soldier for the game. It is hoped that either the official team or modders will implement the capturable Mercenary Camp idea talked about on the forum.
- Building Capturing and Unit Conversion using a "Loyalty" mechanic: Some techs in this mod cannot be implemented yet (or are implemented in a different way) because capturing and loyalty are not implemented. Hopefully this feature is implemented so this mod can add another layer of richness to the gameplay.
- Tech and Aura Modifications: These new modifications need to be implemented for this mod to reach its full potential: Altering Market Bartering recovery rates, Altering technology costs and speeds, (+ others here).

MAJOR OVERALL CHANGES
================
- Completely new unit balance and countering.
- A new 4th Phase: Imperial Phase, which unlocks major technologies and abilities. Requires 2000 Metal and 1 Wonder.
- Civic Centers are now buildable in the 3rd Phase (City Phase). This allows the players time to build up home defenses in Town Phase, or use the stone for a push to City Phase for expansion.
- A completely redesigned technology tree, customized for each civilization. Blacksmith and Fortress trees are especially new.
- Naval gameplay revamped with a Shipyard for the non-barbarian civs. Docks are for naval economy and Shipyard for naval warfare.
- New special buildings, such as the Temple of Vesta for the Romans, with new auras and features.
- Other features.

NEW UNIT BALANCE
===========
The unit balance has been changed. The following list gives the basic changes, including features like charging that are not yet implemented in the full game.

Melee Citizen-Infantry
===========
Sword Infantry
- Cost: 60F 40M
- Health: 100
- Attack: Hack, High
- Bonus: 1.5x vs. Infantry and Elephants
- Charge Bonus: 2x
- Hack Armor: High
- Pierce Armor: Low
- Speed: Medium

Spear Infantry
- Cost: 50F 50W 
- Health: 100
- Attack: Hack, Medium
- Bonus: 2x vs. Cavalry
- Charge Bonus: 2.5x
- Hack Armor: Medium
- Pierce Armor: Medium
- Speed: Medium

Pike Infantry
- Cost: 40F 60W
- Health: 100
- Attack: Hack, Low
- Bonus: 4x vs. Cavalry
- Charge Bonus: 2x
- Hack Armor: High
- Pierce Armor: Medium
- Speed: Low

Ranged Citizen-Infantry
=============================
Archer Infantry
- Cost: 40F 60W
- Health: 80 
- Attack: Pierce, Low
- Range: High
- Accuracy: Low
- Rate: Medium
- Bonus: 1.5x vs. Melee Infantry
- Hack Armor: Low
- Pierce Armor: Medium
- Speed: Medium

Javelin Infantry
- Cost: 40F 60W
- Health: 80
- Attack: Pierce, Medium
- Range: Medium
- Accuracy: Medium
- Rate: Medium
- Bonus: 1.5x vs. Ranged Cavalry, Spear Infantry, and Elephants
- Hack Armor: Low
- Pierce Armor: Medium
- Speed: High

Slinger Infantry 
- Cost: 50F 40S
- Health: 80
- Attack: Pierce, Low
- Range: Medium
- Accuracy: High
- Rate: High
- Bonus: 1.5x vs. Ranged Infantry and Sword Infantry
- Hack Armor: Low
- Pierce Armor: Low
- Speed: High

CITIZEN CAVALRY STATS
=================================================
- Penalty: Horse Cavalry 0.5x vs. Elephants and Camels
- Penalty: Camel .80x Speed
- Bonus: Camel 1.5x vs. Horse Cavalry
- Speed (walk/run/charge): 1.5x Infantry Counterparts

Melee Citizen-Cavalry
=======================
- Bonus: 2x vs. Siege
- Special: Trample Aura/Ability

Sword Cavalry 
- Cost: 80F 40M
- Health: 150
- Attack: Hack, High
- Bonus: 1.5x vs. Ranged Infantry and Ranged Cavalry
- Charge Bonus: 2.5x
- Trample: Low
- Hack Armor: Low
- Pierce Armor: High
- Speed: High

Spear Cavalry: 
- Cost: 80F 50W
- Health: 150
- Attack: Hack, Medium
- Bonus: 2x vs. Ranged Infantry
- Charge Bonus: 4x
- Trample: Medium
- Hack Armor: Medium
- Pierce Armor: High
- Speed: Medium

Ranged Citizen-Cavalry
=============================
Archer Cavalry
- Cost: 100F 50W 
- Health: 130
- Attack: Pierce, Low
- Range: High
- Accuracy: Low
- Rate: Medium
- Bonus: 1.5x vs. Melee Infantry
- Hack Armor: Low
- Pierce Armor: Medium
- Speed: High

Javelin Cavalry
- Cost: 100F 40W
- Health: 130
- Attack: Pierce, Medium
- Range: Medium
- Accuracy: Low
- Rate: Medium
- Bonus: 1.5x vs. Support
- Hack Armor: Low
- Pierce Armor: Low
- Speed: High

Other Melee Units
=================================================
Melee Elephant
- Cost: 150F 100M
- Health: 400
- Attack: Hack, Medium; Crush, High
- Bonus: 2x vs. Cavalry, 1.5x vs. Structures
- Charge Bonus: 3x
- Trample: High
- Hack Armor: Medium
- Pierce Armor: High
- Speed: Low

Other Ranged Units
=================================================

Archer Chariot
- Cost: 100F 100W
- Health: 200 
- Attack: Pierce, Low
- Range: High
- Accuracy: Low
- Rate: Medium
- Trample: High
- Bonus: 1.5x vs. Melee Infantry
- Hack Armor: Medium
- Pierce Armor: Medium
- Speed: Medium

Javelin Chariot
- Cost: 100F 100W
- Health: 200
- Attack: Pierce, Medium
- Range: Medium
- Accuracy: Medium
- Rate: Medium
- Trample: High
- Bonus: 1.5x vs. Support
- Hack Armor: Medium
- Pierce Armor: Medium
- Speed: Medium

Archer Elephant
- Cost: 150F 75W
- Health: 300
- Attack: Pierce, Low
- Range: High
- Accuracy: Medium
- Rate: Medium
- Trample: High
- Bonus: 1.5x vs. Melee Infantry
- Hack Armor: High
- Pierce Armor: Medium
- Speed: Low

Citizen-Soldier Ranks/Promotions
=================================================
- Each new rank improves all stats by about +10% or 1.1x
- Each new rank decreases economic usefulness by about -25%.

Champions
=================================================
- Most stats +50% or 1.5x over their Citizen-Soldier counterparts of Basic Rank
- No economic abilities, though may have various kinds of inspiration auras affecting their citizen counterparts or other units
- Some Champions may have training limits, due to their elite status
- Champions are trained in Battalions/Formations by default (because they don't need to be broken up for fine-tuned economic tasks), except for the Persian Immortals who are trained extremely rapidly individually

Mercenaries
=========================
The following would be the ideal implementation of Mercenaries in the game. Some things this mod is in the process of implementing, but capturing Mercenary Camps and other features (like altering the Camp's ProductionQueue based on who owns it) cannot be implemented until these things are added to the core game.

- Mercenary unit-types available to players based on map biome and the civilization of the owning player
- Trained at Mercenary Camps dotted around the map, capturable by players. The number of camps determined by the number of players: 1 merc camp for 2 players, 2 merc camps for 3-4 players, 3 merc camps for 5-6 players
- Mercenaries cost no population, but can only be trained in limited numbers or are otherwise limited in some way; this is normally the only way a player can train more units above the population cap
- Metal is almost always one of their costs, usually replacing the Food cost
- They do not perform economic tasks, but they can build structures
- They do not contribute to gaining Loot, as they "keep booty for themselves"
- The rest of their stats are comparable to their citizen-soldier counterparts at the Elite rank, and they do not promote to new ranks
- Each mercenary soldier comes with 1-2 tech upgrades researchable at the merc camp when captured by the player. For instance, Balearic Slingers and Rhodian Slingers can have a "Lead Sling Bullets" technology at the Merc Camp, a tech not normally available to civs with those mercs

So, for example: 

An "Egyptian Biome" map like Nile River
- 4 Players
- 2 Mercenary Camps on the map, capturable by any player
- 2 "Egyptian Biome" Mercs available at the Camps: Libyan Skirmisher, Garamantine Camel Raider
- Up to 3 Mercs available, based on the capturing player's civilization: Ptolemies (Mercenary Thureophoros, Nubian Archer, Galatian Swordsman); Seleucids (Mercenary Thureophoros, Thracian Swordsman, Tarantine Cavalry); Spartans (Cretan Mercenary Archer, Rhodian Slinger, Tegean Hoplite); Iberians (Balearic Slinger, Greek Settler Hoplite, Gaesatae).
- None of the mercs cost population room, but all cost an amount of metal, and they are each limited to 20 alive at a time.

CIVILIZATION BONUSES AND CHANGES
=========================
The specific bonuses and changes for each civ. Changes or additions will have an asterisk (*).

Athenians
=======================
+10% Metal gathering for each passing phase.

Britons
=============

Carthaginians
=============

Gauls
=============

Iberians
=============

Macedonians
=============

Mauryans
=============

Persians
=============

Ptolemies
=============

Romans
=============

Seleucids
=============

Spartans
=============
