# Combat Rules

The Crystal Sagas combat system is *roughly* based off of Dungeons and Dragons.

- Event Managers and Administrators reserve the right to alter these, as DMs, when determined necessary. Any complaints regarding rules should be forwarded to an admin ticket for discussion.

## Core Stats

Ontop of the standard stats seen in the character sheet, there are a few particularly important stats for combat:

- [P/M]AB - Accuracy bonus to physical, and magical attacks. These affect the 'to hit' of outgoing attack rolls performed by the system.
- [P/M]DB - Damage bonus to physical, and magical attacks. These directly affect the damage of outgoing attack rolls performed by the system.
- AC - Armor Class. If an attack roll has less to-hit than one's AC, it misses / is deflected harmlessly unless otherwise stated.
- DR - Damage Reduction. This is a flat deduction from **incoming attack rolls.**
    - This applies to every attack roll separately; e.g. a 4-multiattack has this applied to every roll, potentially making this much more powerful on individually lesser multiattacks than powerful, singular attacks.
- Speed - Your default tile movement, usable for your movement action.
    - This is rounded **down** when being divided/penalized, but may **never go below 1** - the only thing that may stop a character from moving is being rooted.
    - Exception: If you are prone, or suffering from another effect that requires a % of your movement action to get out of, you may not move after you get up.

## Combat Flow

By default, combat goes like this:

- Involved characters place down a turn tracker and join the battle, rolling initiative
- The turn order goes from highest to lowest initiative, and loops once a cycle is finished.
- Combat ends once an entire side is fully KO'd.

### Joining Mid Combat

A character joining mid combat will have **one** turn skipped.

- You are considered to be joining mid combat if you were not initially in the turn counter, and both sides have not agreed to void this rule.
- EMs can and will overrule this guideline for events when necessary.

## Action Economy

By default, all characters (players and NPCs) have the follow actions to spend on a given turn:

- 1 **Standard Action**: Anything not listed as a Bonus, Free, or Reaction; This **may** be substituted for a Bonus Action, unless otherwise specified.
- 1 **Bonus Action** - special 'additional' actions that some abilities may mark themselves to use.
- 1 **Reaction** - used for 'reacting' to something, whether it is an attack or otherwise; usually used outside of the character's turn.
- 1 **Movement Action** - You may move up to your **speed** stat in tiles, unless otherwise changed by statue effects/equipment/conditions. This may be taken in multiple parts, **unless** if a perk states it uses the movement action (e.g. Time Mage may not teleport and *then* move their speed, or split their teleport into two actions).
- *Unlimited* **Free Action**s - used for special perks/abilities that are generally not attacks, in specific, niche situations.

Status Effects, perks, etc, may change this.

A character may utilize their Action Economy in **any** order; e.g. you may choose to bonus-action attack, move, and *then* standard action attack, etc.

## Global Mod(ifier)s

As an *obnoxiously* complicated TTRPG-like, Crystal Sagas does not have all of its combat logic encoded in code.

Here is a non-exhaustive list of what needs Global Mods to be used properly:
- Equipment bonuses: Armor, MAB/MDB boosting 'catalyst' weapons
- Perk effects that change based on stacks
- Anything that does not say it is added **passively, automatically, or latently**.

The situation in regards to autmoating some of these - especially equipment bonuses - is being improved with time.

## Combat Conditions

- **Attack of Opportunity**: When moving out of range of a **melee** weapon, the wielder may spend 1 **reaction** to make a standard weapon attack against the moving character.
- **Flanking**: When two characters are next to an enemy, the enemy is considered **flanked**.
    - Flankers gain advantage on **weapon attack rolls** (whether ability, perk, or basic) against the flanked entity.
- **Grappled** - A melee strength-contested roll against another entity to hold them in place.
    - Held entities are considered **rooted** and take **disadvantage** when attacking the grappler. They may not utilize their *basic* movement action (e.g. moving with your speed stat) while this is in effect.
    - To break free, the victim must make a Strength roll against the grappler (meet = beat). This strength roll gains +1 for every turn in a row they are grappled.
    - Grappling something is considered a **Bonus Action**.
- **Prone** - A prone entity must spend half of their standard movement action to get up.
    - Abilities which utilize one's movement action may break one out of this condition immediately. 
    - Attacks against a prone entity have **advantage**.
- **Knock-up** - Applied to entities that are knocked airborne.
    - May be negated by status effects / perks / other.
    - Entities suffering from knock-up are considered **Prone**.
- **Obscured** - If a character is unable to see, they are blind until the offending problem is mitigated.
    - Examples: Thick Fog, Darkness, etc.
- **Exhaustion** - A brutal effect that represents a character becoming too exerted.
    - **This is slated for rework.**
    - For each stack:
    - 1: -1 Tile Movement (cumulative)
    - 2: -2 Tile Movement (cumulative)
    - 3: -2 MAB, -2 PAB
    - 4: -10 to all **direct** outgoing damage via attack rolls
    - 5: +10 to all **direct** incoming damage via attack rolls
    - 6: -3 Tile Movement (cumulative)
    - 7: -4 Tile Movement (cumulative)
    - 8: Disadvantage on all outoging attack rolls
    - 9: Disadvantage on all saving throws
    - 10: Suffer -40 HP at the **start** of each round.
    - Tile Movement may be decreased to a minimum of 1.

## Ability Cooldowns

This system is under development.

Abilities have the following cooldowns:

- C rank: 2 turn
- B rank: 3 turn
- A rank: 4 turn
- S rank: 5 turn

The following exceptions are in effect:

- Multi-attacks have +1 turn CD
- Healing abilities have -1 turn CD
- Limit Break ignores this cooldown, but still places the ability on cooldown once used.

## Fall Damage



## Status Effects

Unlike **Combat Conditions**, these are normally timed effects that expire by themselves (unless manually cured/dispelled by something).

Please see [Status Effects](./status_effects.md).

### Status Cooldowns

## Summons / Robots / NPCs

Two specific points are currently enforced for NPCs of any kind, unless otherwise noted in a perk.

- Due to *current* code limitations, NPCs **act on their summoner's turn, rather than being added to the turn tracker proper.** This will change in the future.
- It takes one **standard** action to deploy **one** NPC unless otherwise noted.

### Summoner

- Summoners may only have **one** summon out unless otherwise stated by perk.
- Summons have a cost as follows:
    - D rank: 25 MP
    - C rank: 50 MP
    - B rank: 80 MP
    - A rank: 100 MP
    - S rank: 150 MP

### Machinists

- To keep it fair to everyone else, **machinists may only have two robots utilized in a fight** - whether this means pulling one out after the other is disabled, or using two standard actions to pull both out.
- Once KO'd, robots must roll to **flee** the battle every turn. If they are hit **again, after KO**, they are broken, and will require materials to repair.

### Other

- All other sources of NPCs are limited to **two per person utilized at the same battle.** This **does not** stack with Summoner/Machinist at the time being. (e.g. you may not utilize faction NPCs with Machinist, though you *may* utilize a summoner summon with Machinist.)
- The Summoner of Yevon, and Pure Red Mage **currently** may utilize their summons on top of any of these caps, without any limitations other than being allowed one concurrent summon for having either job (and two if both) to utilize this. This **may** change in the future, for balancing purposes.
- The Summoner of Yevon has the following costs for summoning their unique summons:
    - Aeon: 90 MP
    - Final Aeon: 200 MP

## Encounters

An 'encounter', for things like limited resources/actions that may only be used # times per encounter, is considered:

- One isolated instance of a PvP battle.
- By default, **an entire dungeon** - unless otherwise specified by the EM.
- By default, **an entire event**, for world events - unless otherwise specified by the EM.

## Danger Level

## PvP


