---
title: Knight
description: 
published: true
date: 2023-11-18T01:04:17.788Z
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

**Key**
🟢  Represents rage generators
🟥  Represents rage spenders

# :crossed_swords: Skills & Spells Overhaul
## New and Modified Spells
:star:**Charge (`utani tempo hur`)**:star: 🟢 100 Rage | :clock2: 12s Cooldown | Level 25 | *Runs rapidly to your target.*
:star:**Phalanx (`utamo scuta`)**:star: 🟥 300 Rage | :clock2: 8s Cooldown | Level 14 | *Support Spell: Generates a shield based on level and defense that transfers 10% of incoming damage to it that lasts up to 30s.*
**Mana Leech** will "heal" your **Phalanx** shield while it's active

## Healing Spells 
**Bruise Bane (`exura infir ico`)** 🟥 100 Rage | :clock2: 2s Cooldown | Level 1
**Wound Cleansing (`exura ico`)** 🟥 100 Rage | :clock2: 2s Cooldown | Level 8
**Fair Wound Cleansing (`exura med ico`)** 🟥 100 Rage | :clock2: 2s Cooldown | Level 300
**Intense Wound Cleansing (``)** No Rage cost | :clock2: 3m (90s with WoD upgrade) Cooldown | Level 80
**Recovery (`exura gran ico`)** No Rage cost | :clock2: 60s Cooldown/Duration | Level 50
**Intense Recovery (`utura gran`)** No Rage cost | :clock2: 60s Cooldown/Duration | 100

## Attack Spells
**Brutal Strike (`exori ico`)** 🟢 350 Rage | :clock2: 2s Cooldown | Level 1
**Front Sweep (`exori min`)** 🟥 250 Rage | 🧛‍♂️ 50% Life Leech | :clock2: 2s Cooldown | Level 20
**Whirlwind Throw (`exori hur`)** 🟥 100 Rage | :clock2: 2s Cooldown | Level 28
**Groundshaker (`exori mas`)** No Rage cost | :clock2: 16s Cooldown | Level 33
**Berserk (`exori`)** 🟢 400 Rage | :clock2: 2s Cooldown | Level 35
**Inflict Wound (`utori kor`)** No Rage Cost | :clock2: 30s Cooldown | Level 40
**Fierce Berserk (`exori gran`)** 🟥 350 Rage (300 with WoD upgrade) | :clock2: 2s Cooldown | Level 50
**Annihilation (`exori gran ico`)** 🟥 600 Rage | :clock2: 8s Cooldown | Level 110
**Executioner's Throw (`exori amp kor`)** 🟥 1000 Rage | :broken_heart: 30% maximum health | :clock2: 8s Cooldown | Wheel of Destiny



## Support Spells
**Challenge (`exeta res`)** 🟢 300 | :clock2: 4s Cooldown | Level 20
**Train Party (`utito mas sio`)** No Rage cost | :clock2: 10s | Level 32
**Protector (`utamo tempo`)** No Rage cost | :clock2: 6s Cooldown | Level 55
**Blood Rage (`utito tempo`)** :broken_heart: 10% current HP | :clock2: 6s Cooldown | Level 60
**Chivalrous Challenge (`exeta amp res`)** 🟥 150 Rage (No rage cost with WoD upgrade) | :clock2: 4s Cooldown | Level 150
**Knight Familiar (`utevo gran res eq`)** :broken_heart: 30% max HP | Level 200

## Adjustments
**Mana Potions** | **Mana Fluids** Using any mana potions on a knight will not add any resources
**Jean Pierre Items** Foods that restore mana will not restore knights resource
**Food and Regeneration Item** Regeneration from food and items do not affect rage resource
**Mana Leech** Does nothing unless **Phalanx** is active, in which case it applies to the shield. Has been removed as an option from *weapons* (but kept around in *helmets*).