---
title: Paladin
description: 
published: true
date: 2023-11-28T01:21:35.194Z
tags: 
editor: markdown
dateCreated: 2023-11-28T01:21:35.194Z
---

## 🏹 Paladin

### 🛡️ Monster Armor
Physical damage to monsters tend to double dip into damage reductions. Armor and physical resistance both cause pure physical damages, such as arrows, bolts, and certain knight weapons to perform very low. For example, a Falcon Longsword would deal less single target auto-attack damage than a Falcon Battleaxe purely from the elemental property of its damage. This is just an outdated mechanic leftover from the old days and doesn't really have a place in a more modern implementation.
- Armor is removed from monsters
- The damage reduction from armor is applied evenly to monster mitigation

### 🌟 Spell & Rune Adjustments
We're shifting some of the damage around in the paladin toolkit to provide space for Focus to take a role within the damage output.
- **Divine Caldera**
  - Base damage reduced by 15% 
  - Sharpshooter enhancement damage reduced
- **Divine Missile**
  - Base damage increased by 100%
  - Sharpshooter enhancement damage increased
  - Base number of targets increased to 6
  - Sharpshooter enhancement targets increased to 10
  - Cooldown is now 4 seconds
- **Holy Missile**
  - Chain rune (5 targets) slightly weaker than Divine Missile
  - Usable by all vocations
- **Divine Rain 🆕 NEW RUNE**
  - Area of Effect rune
  - Usable by all vocations
  - Paladins deal increased damage with this rune
- **Divine Empowerment**
 - Damage buff has been removed
 - Provides magic level (+3/+5/+7) while within the zone
 - Creatures that walk into empowerment fields are challenged by the paladin for 5 seconds
 - Area of effect increased
- **Divine Grenade**
 - Area of effect increased
 - Damage increased _substantially_
 - Cooldown changed (30s/26s/20s)

### ⚡ Dexterity Changes
- In addition to increasing dodge chance, dexterity will also increase basic attack speed for all vocations. 
  - Each dexterity level decreases auto-attack delay by 1.5ms (up to a minimum total reduction of 33%)
  - This bonus stacks with sword speed increases

### 🎯 Focus
- Maximum of 1000 focus 
- At 1000 focus, paladin auto-attack delay is 1.2 seconds (current baseline is 2.0 seconds)
- Focus is generated at the rate of 50 focus per second in combat when attacking 
- Being struck with a melee attack will result in losing 100 focus
- Focus is represented by the purple bar used for magic shield and phalanx

### 🏹 Ammunition Changes
- **Arrows**
  - Area of effect slightly increased
- **Bolts**
  - Damage per shot reduced by half
  - Note that attack speed at full focus doubles attack rate, which offsets this reduction
- **Throwables** (spears/stars/etc)
  - Damage reduced by 15%

### 🏁 Goals
- **Distance Skill Role**
  - Distributes paladin AoE damage between magic level and distance fighting
- **Rewarding Mechanic**
  - Focus adds a dynamic layer, offering strategic depth to gameplay in group and solo play
- **Role Definition**
  - Current paladin and knight play very similarly, this change looks to make definition between gameplay styles 
  - While fulfilling a tank role in a party (main or offtank), damage output will be slightly lower
  - While providing a pure dps role to party, damage potential rises
  - Spells reworked to fit tank/dps roles in an intuitive way
- **Maintain Current Gameplay Options**
  - Similar to the Knight rework, we want to maintain the feel of the paladin class
  - Using a **Focus** gameplay style is completely optional