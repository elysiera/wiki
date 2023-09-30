---
title: Server Info
description: 
published: true
date: 2023-09-30T06:00:06.168Z
tags: 
editor: markdown
dateCreated: 2023-09-30T06:00:06.168Z
---

## General Info
- **Protocol**: 13.21
- **Server type**: non-PVP
- **Location**: Montreal - Canada
- **Loot rate**: 2✕
- **Autoloot & Autobank**: Manage containers in-game for loot, gold goes directly to your bank account.
- **Greater security**: `bcrypt` salted and encrypted password, optional 2-factor-authentication
- **Weekly Vouchers**:
  - 4 hours of double experience
  - 12 hours of double skill
- **Free quests**: Access quests unlocked so you can hunt spawns and the bosses you want

## Training
- **Free, infinite, training weapons**: This are 20% as effective as regular exercise weapons, but last forever!
- **Basic exercise weapons**: Baseline weapons (5x more effective than the infinite ones). You get  them in game at [Online Points](https://elysiera.com/pages/online-points) store, for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)
- **Enhanced exercise weapons**: 20% more effective than _Basic_. You get get them in ganme for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)
- **Masterful exercise weapons**: 30% more effective than _Basic_. You get get them in ganme for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)

## Blessings
- All 7 regular blessings available (you start with the basic 5 for free)
- Use `!bless` in game to buy blessings
- Free until level 100
- From level 101 -> 399: `(level - 100) * 60 + 1000` _(per blessing)_
- Levels 400+: 20,000 _(per blessing)_

## Level rewards

You get some basic gold rewards at a few levels:
- Level 50: 20,000 gold
- Level 100: 50,000 gold
- Level 150: 100,000 gold
- Level 200: 200,000 gold

And you also get unique tokens at _every_ level between 50 and 500:

- Levels 1-49: No tokens.
- Levels 50-99: 5 Copper tokens per level.
- Levels 100-149: 5 Iron tokens per level.
- Levels 150-199: 5 Platinum tokens per level.
- Levels 200-500: 5 Titanium tokens per level.

### Token NPCs
Elysiera features special NPCs called Quartermasters, who trade equipment and items in exchange for tokens. There are four Quartermasters, each corresponding to a type of token:

- Titanium Quartermaster: Exercise weapons, prey cards, etc.
- Platinum Quartermaster: Trades mid-high-level equipment for Platinum tokens.
- Iron Quartermaster: Trades mid-level equipment for Iron tokens.
- Copper Quartermaster: Trades low-level equipment for Copper tokens.


## Custom systems
- Diamond arrows are 1sqm larger and deal more damage.
- Wands/rods damage scale up with magic level and level, and can chain up to 4 creatures
- All melee skills have been merged into **Melee fighting**.
  - Swords are powerful single target weapons that deal more damage faster
    (+20% attack speed, regular damage formula).
  - Axes can chain up to 5 creatures that are standing besides eachother
    (-20% damage).
  - Clubs deal area damage the same size as _diamond arrows_
    (-50% damage).
  - All training weapons and imbuments that previously affected sword, axe or club will affect melee. Fist fight fighting is melee and has been slightly buffed.
- _New skill_  **Runic fighting**: You level up _runic fighting_ everytime you damage an enemy with a rune. Runes receive a boost in damage based on the caster's runic skill.
- _New skill_  **Luck**: You level up _luck_ by looting rare items. Luck gives you more loot and also gives you _critical hit chance_!
-  Every character starts with a base of 50% critical hit damage. This adds up with imbuments. For example, a player with a Powerful Strike imbument will deal 100% critical damage.
-  _New skill_  **Tonicity**: You level up _tonicity_ by simply drinking potions. Higher tonicity makes potions slightly more effective. Their biggest impact is on the _average_ healing of a potion though, not the maximum.
-  _New skill_  **Dexterity**: You level up _dexterity_ by simply taking damage. The more damage you take, the more you'll level up this skill. Currently dexterity only provides a small passive chance of triggering "dodge".
-  The _MAXIMUM_ resistance any creature can have to any element is 30%. This means that every element is somewhat viable in every situation.

## Some Spell Changes

**Divine Dazzle:** 
- Chains on 5 creatures (base)
- Works on melee creatures (if they can run on low health)
- Prevents creatures from running on low health
- Skips already affected creatures

**Chivalrous Challenge:**
- chains on 6 creatures (base)
- skips already affected creatures

**Challenge:**
- Changes ranged creatures to melee (except for bosses)

**Train Party:**
- increases party skills by 2% (primary skill; i.e. magic for mages, distance for paladins, does not affect other knights) (does not stack with other knights)

**Protect Party:**
- decreases party members damage take by 1%

**Heal Party:**

- 30 health per second (instead of 20 every 2)

**Divine Missile**
- added chain effect to spell, effecting up to 5 targets
- _**Developer notes:** Divine Missile and Ethereal Spear are nearly identical. We wanted to define a situational usage for one spell over the other._

**Rune Rebalancing:**
- _Fireball:_ Damage increased to approximately 90% of Sudden Death.
- _Heavy Magic Missile:_ Damage increased to approximately 90% of Sudden Death.
- _Icicle:_ Damage increased to approximately 90% of Sudden Death.
- _Stalagmite:_ Damage increased to approximately 90% of Sudden Death.
- _**Developer notes:** We want to give outdated runes a situational use. The Sudden Death rune has been the goto rune for single target. Certain monster resistances or vulnerabilities will give the player the option to optimize damage with elemental runes._ 

## Rates

**Experience Stages**

{% table .table %}
* Level range
* Rate
---
* 1 – 9
* 10✕
---
* 10 – 29
* 25✕
---
* 30 – 59
* 50✕
---
* 60 – 99
* 45✕
---
* 100 – 149
* 40✕
---
* 150 – 199
* 35✕
---
* 200 – 249
* 30✕
---
* 250 – 299
* 25✕
---
* 300 – 399
* 20✕
---
* 400 – 499
* 15✕
---
* 500 – 699
* 10✕
---
* 700 – 999
* 5✕
---
* 1000 – ∞
* 3✕
{% /table %}

**Magic Level Stages**

{% table .table %}
* Magic range
* Rate
---
* 0 – 60
* 6✕
---
* 61 – 80
* 15✕
---
* 81 – 100
* 10✕
---
* 101 – ∞
* 5✕
{% /table %}

**Skill Stages**

{% table .table %}
* Skill range
* Rate
---
* 10 – 60
* 40✕
---
* 61 – 80
* 30✕
---
* 81 – 110
* 15✕
---
* 111 – 125
* 10✕
---
* 126 – ∞
* 5✕
{% /table %}
