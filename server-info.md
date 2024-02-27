---
title: Server Info
description: 
published: true
date: 2024-02-27T02:07:50.531Z
tags: 
editor: markdown
dateCreated: 2023-09-30T06:00:06.168Z
---

## General Info

-   **Protocol**: 13.30
-   **Server type**: non-PVP
-   **Location**: Montreal - Canada
-   **Autoloot & Autobank**: Manage containers in-game for loot, gold goes directly to your bank account.
-   **Greater security**: `bcrypt` salted and encrypted password, optional 2-factor-authentication
-   **Weekly Vouchers**:
    -   4 hours of double experience (Refreshed on Wednesday)
    -   12 hours of double skill (Refreshed on Thursday)
-   **Free quests**: Access quests unlocked so you can hunt spawns and the bosses you want

## Important differences compared to retail Tibia

- Damage and Healing Revelation Perk on Wheel of Destiny is **quadrupled**! For instance, if the tooltip says you have +9 damage/healing, you actually have +36.
- Boss cooldowns are 10 hours instead of 20.
- Max resistance of mobs against any element is 30%, so you deal at least 70% damage with any element against any mob (including bosses).
- No mobs (including bosses) reflect damage.
- No mobs (including bosses) heal due to taking damage from any element.
- **Prey improvement:** Killing mobs which are not your preyed mobs do not drain the remaining prey durations.
- **Imbue improvements:** Costs gold only, no creature parts required. Can choose between a 5-hour option or a 20-hour option (which costs 4 times more). 5-hour costs are 2750 (basic), 20000 (intricate), and 300000 (powerful).
- **Silver Token items:** Are now permament and no longer need to be recharged! Also, they can be upgraded using the Forge (see below).
- **Exaltation Forge improvements:** 
	- Class 1 items can be upgraded to Tier 3 (Tier 1: 25k, Tier 			2: 50k, Tier 3: 100k).
  - Class 2 items can be upgraded to Tier 4 (Tier 1: 50k, Tier 			2: 100k, Tier 3: 200k, Tier 4: 400k).
  - Class 3 items can be upgraded to Tier 5 (Tier 1: 200k, Tier 2: 400k, Tier 3: 800k, Tier 4: 1.6m, Tier 5: 3.2m).
  - Class 4 items can be upgraded to Tier 10 (Tier 1: 1.5m, Tier 2: 3m, Tier 3: 6m, Tier 4: 15m, Tier 5: 30m, Tier 6: 80m, Tier 7: 200m, Tier 8: 400m, Tier 9: 800m, Tier 10: 1.6b).
- **New Exaltation Forge perks:**
	- Helmets: +1 arm in addition to Momentum
	- Armors: +1 arm in addition to Ruse
	- Legs: +1 arm in addition to Transcendance
	- 2-handed weapons: +1 atk in addition to Onslaught
	- 1-handed weapons: +0.5 atk and +1 extra defense in addition to Onslaught
	- Wands/Rods: +0.5 magic level in addition to Onslaught
	- Bow: +0.5 atk and +0.5 atk speed in addition to Onslaught
	- Crossbow: +0.5 atk and +0.5 hit% in addition to Onslaught
- **Dynamic spawn:** For most spawns, mob density and cluster distribution changes on every Server Save, in a completely random manner.

## Rates

**Experience:** 10✕ at start, ramping down to 2✕ at lvl 1000
![exp-rate.png](/exp-rate.png)

**Loot**: 1.5✕

**Skills/Magic Level:** 3✕

## Training

-   **Free, infinite, training weapons**: They have 20% or 1/5 of the effectiveness of exercise weapons, but they last forever!
-   **Basic exercise weapons**: Baseline weapons (5x more effective than the infinite ones). You get them in game at store, for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)
-   **Enhanced exercise weapons**: 20% more effective than *Basic*. You get get them in game for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)
-   **Masterful exercise weapons**: 30% more effective than *Basic*. You get get them in game for gold, tokens or [Elysiera Coins](https://elysiera.com/shop)

## Blessings

-   All 7 regular blessings available (you start with the basic 5 for free)
-   Use `!bless` in game to buy blessings
-   Free until level 100
-   From level 101 -> 399: `(level - 100) * 60 + 1000` *(per blessing)*
-   Levels 400+: 20,000 *(per blessing)*

## Wheel of Destiny chances

- Mitigation multiplier, life leech, mana leech are 4 times more effective. This means you get 0.12% mitigation multiplier per point, 3% life leech and 1% mana leech per node.
- Healing and damage boosts are 10 times more effective, giving you a total of 40 as boost instead of 4 per stage.

## Level rewards

You get some basic gold rewards at a few levels:

-   Level 8: 20 Hunter Tokens
-   Level 50: 20,000 gold
-   Level 100: 50,000 gold
-   Level 150: 100,000 gold
-   Level 200: 200,000 gold

## Server Commands
#### **General commands:**
-   **!commands**
See a list of commands available
-   **!aol**
Spawn an Amulet of Loss into your backpack (Costs 50,000 gold)
- **!autoloot on | !autoloot off**
Enable or disable autoloot
-   **!bless**
Add all available blessings.
-   **!vip**
Check your VIP status
-   **!flask on	 | !flask off**
Enables or disables receiving empty flasks when drinking potions
-   **!emote on	 | !emote off**
On will make spells display in chat.
Off will remove spells from chat and display as an emote (Orange text)
-   **!online**
Lists all players online and their current status
-   **!serverinfo**
Lists the server status
-   **!time**
Displays the current game world time


#### **Bank commands**
*Do not include the (brackets) when typing these commands*
-   **!withdraw (amount)**
Withdraw money from your bank
-   **!transfer (player name), (amount)**
Send money to another player
-   **!balance**
Check your bank balance
-   **!deposit (amount) *or* !deposit all**
Deposit a specific amount of money in your backpack to your bank.
Or deposit all money in your backpack into your bank.

#### **Housing commands:**
-   **!buyhouse**
Stand in front of the door to buy the house.
-   **!leavehouse**
Stand inside of the house to abandon the house.
-   **!sellhouse**
Stand in front of the door, have another player nearby, click them and it will initiate a trade to sell them the house.

## Custom systems

-   Diamond arrows are 1sqm larger and deal more damage. They are also impacted by elemental imbuements on bows.
-   Wands/rods damage scale up with magic level and level, and can chain up to 4 creatures
-   All melee skills have been merged into **Melee fighting**.
    -   Swords are powerful single target weapons that deal more damage faster  
        (+20% attack speed, regular damage formula).
    -   Axes can chain up to 5 creatures that are standing besides eachother  
        (-20% damage).
    -   Clubs deal area damage the same size as *diamond arrows*  
        (-50% damage).
    -   All training weapons and imbuments that previously affected sword, axe or club will affect melee. Fist fight fighting is melee and has been slightly buffed.
-   *New skill* **Runic fighting**: You level up *runic fighting* everytime you damage an enemy with a rune. Runes receive a boost in damage based on the caster's runic skill. This skill levels up faster the more monsters you hit with a rune; damage dealt is irrelevant!
-   *New skill* **Luck**: You level up *luck* by looting rare items. Luck gives you more loot and also gives you *critical hit chance*!
-   Every character starts with a base of 50% critical hit damage. This adds up with imbuments. For example, a player with a Powerful Strike imbument will deal 100% critical damage.
-   *New skill* **Tonicity**: You level up *tonicity* by simply drinking potions. Higher tonicity makes potions more effective, in terms of both their minimum and maximum output.
-   *New skill* **Dexterity**: You level up *dexterity* by simply taking damage. The more damage you take, the more you'll level up this skill. Currently dexterity only provides a small passive chance of triggering "dodge".
-   The *MAXIMUM* resistance any creature can have to any element is 30%. This means that every element is somewhat viable in every situation.