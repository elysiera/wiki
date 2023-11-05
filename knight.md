---
title: Knight
description: 
published: true
date: 2023-11-05T06:30:39.056Z
tags: 
editor: markdown
dateCreated: 2023-11-05T06:22:08.064Z
---

# Knight

Knights are the only vocation that actively mange both health and mana potions. Due to their shared cooldown, this often leads to situations where the choice is to only drink health potions to survive, while being unable to recover mana to break free from a surround. Additionally, knights have suffered a disproportionate impact from mana drain mechanics. This rework completely removes mana drain's effects on a knight's resource. Finally, knights' single-target spell options have felt underwhelming. 

We are reworking the knight's resource system and redesigning all knight abilities to work within. By refining the resource system, knights can now simultaneously manage health and combat resource independently, offering a smoother and more controlled battle rhythm. This change is also impactful in the early game, allowing for a progression system that feels just as viable as other vocations. To address knight's single target rotations, certain spells have been redefined with a clear strategic purpose, providing a niche to many of the underutilized abilities. These adjustments are designed to elevate the knights' playstyle, providing a richer and more robust combat experience.

# :new: New Resource: Rage
- **Maximum Rage**: 1000 points
- **Rage Mechanics**: Replaces mana. Increases with designated combat actions; passively decays or regenerates towards a baseline of 200.
- **Developer Notes**: We aim to create a more dynamic combat system, where resource management becomes crucial to your success on the battlefield.

# :crossed_swords: Skills & Spells Overhaul
## New and Modified Spells
:star:**Charge**:star: 🟢 100 Rage | :clock2: 12s Cooldown | Level 25 | *Runs rapidly to your target.*
:star:**Phalanx**:star: :red_square: 300 Rage | :clock2: 12s Cooldown | Level 14 | *Support Spell: Generates a shield based on level and defense that transfers 10% of incoming damage to it.*

## Healing Spells 
**Bruise Bane** :red_square: 100 Rage | :clock2: 2s Cooldown | Level 1
**Wound Cleansing** :red_square: 100 Rage | :clock2: 2s Cooldown | Level 8
**Fair Wound Cleansing** :red_square: 100 Rage | :clock2: 2s Cooldown | Level 300
** Intense Wound Cleansing** No Rage cost | :clock2: 3m Cooldown | Level 80
** Recovery** No Rage cost | :clock2: 60s Cooldown/Duration | Level 50
**Intense Recovery** No Rage cost | :clock2: 60s Cooldown/Duration | 100

## Attack Spells
 **Brutal Strike** 🟢 350 Rage | :clock2: 2s Cooldown | Level 1
 **Annihilation** :red_square: 600 Rage | :clock2: 8s Cooldown | Level 110
 **Whirlwind Throw** :red_square: 100 Rage | :clock2: 8s Cooldown | Level 28
 **Executioner's Throw** :red_square: 1000 Rage | :broken_heart: 30% maximum health | :clock2: 8s Cooldown | Wheel of Destiny
 **Groundshaker** No Rage cost | :clock2: 16s Cooldown | Level 33
 **Berserk** 🟢 400 Rage | :clock2: 2s Cooldown | Level 35
 **Fierce Berserk** :red_square: 350 Rage | :clock2: 2s Cooldown | Level 50
 **Front Sweep** :red_square: 250 Rage | :man_vampire: 50% Life Leech | :clock2: 4s Cooldown | Level 20
 **Inflict Wound** No Rage Cost | :clock2: 30s Cooldown | Level 40

## Support Spells
**Challenge** 🟢 300 | :clock2: 4s Cooldown | Level 20
**Chivalrous Challenge** :red_square: 15 Rage | :clock2: 4s Cooldown | Level 150
**Train Party** No Rage cost | :clock2: 10s | Level 32
**Protector** No Rage cost | :clock2: 6s Cooldown | Level 55
**Blood Rage** :broken_heart: 10% current HP | :clock2: 6s Cooldown | Level 60
**Summon Knight Familiar** :broken_heart: 30% max HP | Level 200

## Item Adjustments
**Mana Potions** | **Mana Fluids** Using any mana potions on a knight will not add any resources
**Jean Pierre Items** Foods that restore mana will not restore knights resource
**Food and Regeneration Item** Regeneration from food and items do not affect rage resource