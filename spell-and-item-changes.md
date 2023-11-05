---
title: Spell and Item changes
description: 
published: true
date: 2023-11-05T06:27:00.705Z
tags: 
editor: markdown
dateCreated: 2023-10-14T10:23:17.790Z
---

# Spell and Item changes

Elysiera introduces a number of changes to many items, and spells.

## Item Changes
- All arrows deal damage in a 5x5 area of effect.
- Bolts remain single target.
- Basic arrows are infinite.
- Basic bolts are infinite.
- Wands and Rods now have their own attack values, scale with Magic Level and Chain to multiple targets. (4 base)
- All throwing weapons chain to up to 5 targets.
- Imbuments only cost **Gold**, no materials.

**Runes revamped**
- AOE runes (Great Fireball, etc) damage increased by ~**26%**.
**Single Target rune revamp:**
- Fireball now chains to up to 5 targets. Deals **10%** less damage than Sudden Death.
- Stalagmite now chains to up to 5 targets. Deals **10%** less damage than Sudden Death.
- Icicle now chains to up to 5 targets. Deals **10%** less damage than Sudden Death.
- Heavy Magic Missile now chains to up to 5 targets. Deals **10%** less damage than Sudden Death.
***Developer notes:** We wanted to give outdated runes a situational use. The Sudden Death rune has been the goto rune for single target. Certain monster resistances or vulnerabilities will give the player the option to optimize damage with elemental runes.*

## Paladin spell changes
**Divine Dazzle:**

-   Words: `exana amp res`
-   Chain effect, up to 5 targets (base)
-   Works on melee creatures (if they can run on low health)
-   Prevents creatures from running on low health
-   Skips already affected creatures

**Protect Party:**

-   Words: `utamo mas sio`
-   Decreases party members damage take by **1%**.

**Divine Missile**
-   Words: `exori san`
-   Chain effect, up to 5 targets.
-   ***Developer notes:** Divine Missile and Ethereal Spear are nearly identical. We wanted to define a situational usage for one spell over the other.*

**Sharpshooter**
Skill has been completely revamped.
- Words: `utito tempo san`
- Now grants 1 charge instead of boosting damage. Charge will allow you to change the effect of one of the following skills:
- *Ethereal Spear*: Fires 5 times for -25% damage per shot.
- *Strong Ethereal Spear*: Deals +10% damage and changes its element to the targets lowest elemental resistance.
- *Divine Missile*: +20% damage and Chains to 3 additional targets.
- *Divine Caldera*: Increases damage by 10% and casts twice. Second cast costs no mana.

*Rank 2 of Augmented Sharpshooter Wheel of Destiny conviction gives 2 charges instead of 1*

**New spell: Conjure Royal Star**
- Words: `exevo gran con grav`
- Creates 30 Royal Stars for 1,000 mana
- Requires level 150

**New spell: Conjure Spectral Bolts**
- Words: `exevo gran con vis`
- Creates 100 Spectral Bolts for 1,000 mana
- Requires level 150

**New spell: Conjure Diamond Arrows**
- Words: `exevo gran con hur`
- Creates 100 Diamond Arrows for 1,000 mana
- Requires level 150

**New Spell: Create Blank Rune**
- Words: `adori blank`
- Creates 1 blank rune for 50 mana and 1 soul point.
- Cannot be cast in a protection zone

## Knight skill changes
**Chivalrous Challenge:**
- Words: `exeta amp res`
-   Chain effect on up to 6 targets (base)
-   Skips already affected creatures
-   Ranged targets rush into melee range (except for bosses)

**Train Party:**
- Words: `utito mas sio`
-   Increases party skills by **2%** (primary skill; i.e. magic for mages, distance for paladins, does not affect other knights) (does not stack with other knights)

**Berserk**
- Words: `exori`
- Damage increased by ~**33%**.

**Fierce Berserk**
- Words: `exori gran`
- Damage increased by ~**25%**

Wheel of Destiny conviction augment further increases damage by +**20%**.

## Druid spell changes

**Heal Party:**
- Words: `utura mas sio`
-   30 health per second (instead of 20 every 2)

## Sorcerer & Druid changes

**New Spell: Create Blank Rune**
- Words: `adori bank`
- Creates 1 blank rune for 50 mana and 1 soul point.
- Cannot be cast in a protection zone

---

**Magic Shield**
- Words: `utamo vita`
- Magic Shield now completely absorbs 40% of all damage taken. It costs no mana upon taking damage.
- Grants a shield of 300 + 7.6 x level + 7 x magic-level. The mana cost to cast the spell is 50% of the amount of shield it provides.
- Example: If you're level 500 with magic level 100 you'll get 4800 magic shield points (purple bar). Casting utamo vita will cost 2400 mana. When you take damage, 40% will go to that shield instead, the other 60% will go to your health.
- Magic shield nodes on Wheel of Destiny also affect this shield.

---

**Strong Strike and Ultimate Strike spells have been overhauled.**
- Strong Words: `exori gran flam`, `exori gran frigo`, `exori gran tera`, `exori gran vis`
- Ultimate Words: `exori max flam`, `exori max frigo`, `exori max tera`, `exori max vis`
- Strong Strikes all share the same cooldown
- Strong Strikes cooldown reduced to 6 seconds
- Strong Strikes deal 60% of Sudden Death damage
- Ultimate Strikes deal 80% of Sudden Death damage

**Strong Strikes now give a stacking buff called Elemental Charge.**
- Capped at 3
- Stack lasts for 10 seconds (Stacks refresh when casting Strong Strikes)

Casting the next Ultimate Strike while having stacks of Elemental Charge will multiply the damage by 1+stacks (4x at max stacks)

## Outfits and other misc cosmetic changes

All changes affect both the base outfit and the addons.

**Druid outfit and addons**
- Requires **25** wolf paws instead of 50.
- Requires **25** bear paws instead of 50.
- Requires **50** demon dust instead of 100.

**Assassin outfit and addons**
- Requires **15** beholder eyes instead of 30.
- Requires **5** red dragon scales instead of 10.
- Requires **25** green, red, blue, white, brown, yellow pieces of cloth instead of 50.
- Requires **5** spools of yarn instead of 10.

**Citizen outfit and addons**
- Requires **50** chicken feathers instead of 100.

**Barbarian outfit and addons**
- Requires **50** spools of yarn instead of 100.
- Requires **25** Red and Green pieces of cloth instead of 50.

**Warrior outfit and addons**
- Requires **50** turtle shells instead of 100.

**Knight outfit and addons**
- Requires **50** behemoth fangs instead of 100

**Wizard outfit and addons**
- Requires **30** holy orchids instead of 50.

**Mage/Summoner outfit and addons**
- Requires **5** spider silk yarn instead of 10.
- Requires **20** holy orchids instead of 35.
- Requires **20** red dragon scales instead of 20.
- Requires **20** vampire dust instead of 30.
- Requires **10** ankhs instead of 20.

**Oriental outfit and addons**
- Requires **50** blue pieces of cloth instead of 100.
- Requires **50** ape furs instead of 100.

**Rascoohan outfit and addons**
- Unlocked by killing Ratmiral Blackwhiskers.
- Addon #1 unlocked by obtaining and using the Soap item, dropped by Ratmiral Blackwhiskers.
- Addon #2 unlocked by obtaining and using the Scrubbing Brush item, dropped by Ratmiral Blackwhiskers.

**Vocation familiars**
- All alternate Familiar appearances can be unlocked by obtaining and using the **Cheesy Key** from Ratmiral Blackwhiskers.