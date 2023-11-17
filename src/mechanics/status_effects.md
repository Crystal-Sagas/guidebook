# Status Effects

Various status effects.

## Ticks

Effect ticks, much like in DND, process at the **end** of turns. This reduces their duration by 1 tick, removing it if it goes to 0.

- If you get Haste for 1 turn this way, you get to use it instead of having it instantly expiring.

## Default Durations

Given we are lacking durations in some ability descriptions, we currently enforce the current default durations when **not specified otherwise**.

Each one provides examples.

- Anything that requires **active (bonus) action** to maintain (e.g. 'use bonus action to move the AoE') lasts for **1** turn after someone starts their turn in it.
- Any **damaging / inaccuracy debuffs** last 3 turns after application by default, unless cured.
    - Fire
    - Frostbite
- Any **partially incapacitating effects** last 2 turns after application by default, unless cured.
    - Stun
    - Paralyze
- Any **fully incapacitating effects** last 1 turn after application by default, unless cured.
    - Stop

## Positive Effects

- Blink:
    - User enforces **disadvantage** against all non-saving-throw attacks or effects against them.
    - User can dispel this effect to enforce **resistance** (halved damage) against the attack, **after** DR calculations.
- Bravery:
    - User rolls all **physical** outgoing attacks at **advantage**.
    - User gains **+4** damage to all **physical** outgoing attacks.
- Bubble:
    - User gains a shield equal to **10% of their Max HP** or **5 x CON modifier**.
    - This shield recharges at the **end** of their turn.  
- Faith:
    - User rolls all **magical** outgoing attacks at **advantage**.
    - User gains **+8** damage to all **magical** outgoing attacks.
- Float:
    - User is **immune** to **earth** damage.
    - User is no longer **knocked up** from being airborne or suffers **fall damage.**
    - Negated by **Heavy**.
- Haste:
    - User gains **+2** Tile Movement.
    - User gains **+3** Armor Class.
- Invisibility:
    - User cannot be targeted unless the attacker has a sensory perk that can detect the user.
    - User gains **advantage** on attacks.
    - **Removed** when the user attacks, unless mentioned otherwise.
- Protect:
    - User gains **10** Damage Reduction against **physical** damage, or **1.5x their physical DR**, whichever is higher.
- Refresh:
    - Restores either **5% of max** or **5 x CON modifier**, whichever is higher, of the user's MP and SP.
- Regen:
    - Restores either **5% of max** or **5 x CON modifier**, whichever is higher, of the user's HP.
    - Negated by **Poison**.
- Reraise:
    - User is **revived** to **50% HP/MP/SP** when they are KO'd, or killed.
    - User has **Resurrection Sickness** inflicted on them for 3 turns.
    - User has **1** stack of **exhaustion** inflicted on them on revival.
    - Negated by **Doom**.
- Safe:
    - User blocks the **first negative status effect** inflicted on them while this is active, dispelling Safe in the process.
- Shell:
    - User gains **10** Damage Reduction against **magical** damage, or **1.5x their magical DR**, whichever is higher.
- Veil:
    - User enforces **disadvantage** against all **incoming** attacks/effects utilizing **saving throws**.
    - User may dispel this when struck by an incoming attack using a **saving throw** to enforce **resistance** (halving the damage) against the attack, **after** DR calculations.. 

## Negative Effects

- Beserk:
    - User gains **+4** accuracy (to hit) and **+4** damage on all **outgoing physical** attacks.
    - User gains **+1** Tile Movement.
    - User may not use **abilities, skills, or reactions.**
    - User must make a **Wisdom** saving throw against the inflicting attack/cause's DC or attack the person closest to them, including allies.
- Bleed:
    - User loses **5 x CON modifier** every turn, or 5 HP, whatever is higher, **bypasssing DR**.
    - This effect may **stack**.
    - Negated by **Regen**.
- Blind:
    - User loses **-5** to their to hit.
    - User loses **-4** to their AC.
- Break:
    - User loses **-2** to their Tile Movement per tick.
    - User is **rooted** and petrified, gaining **resistance** to all **physical** damage, when they run out of tile movement.
    - User becomes a statue on the next tick after this, gaining **+10** Armor Class, **vulnerability** to all **physical** damage.
    - User **dies** when KO'd while Petrified.
    - Unlike other effects, this is permanent until dispelled manually.
- Burn:
    - User has their **outgoing physical** damage **halved**.
    - Dispelled by any **cold** damage towards the user.
- Curse:
    Any kind of restorative magic harms the user, instead of heals.
- Doom:
    - User is marked for death.
    - User is **KO'd** if this is not dispelled within 4 turns.
    - Negated by **Reraise** (Reraise instantly activates on this going off).
- Frostbite:
    - User has their **outgoing magical** damage **halved**.
    - Dispelled by any **fire** damage towards the user.
- Heavy:
    - User suffers **-2** Tile Movement.
    - User suffers **-2** Armor Class.
    - User suffers **vulnerability** (doubled damage) to **Earth** damage.
    - User is **grounded** and unable to fly.
    - Negated by **Float**.
- Paralyze:
    - User is **rooted**, and unable to move.
    - User automatically fails **Strength** and **Dexterity** saving throws.
    - User is considered **Prone**.
    - Airborne targets are immediately knocked to the ground.
- Poison:
    - User loses **5% max HP**, or **5 x CON modifier** every tick, whichever is higher.
    - User makes all **outgoing attacks** and **ability / skill rolls** at **disadvantage**.
    - Negated by **Regen**.
- Resurrection Sickness
    - Prevents resurrection until expired / cured.
- Silence:
    - User is unable to use **General, Black, and White** magic.
    - User is unable to **talk**.
- Sleep:
    - User has **0 AC**, and **incoming, adjacent attacks** against the user are made with **advantage**.
    - User must make a **Wisdom** saving throw against the source's DC to wake up.
    - User gains **20 HP/MP/SP** per tick while asleep.
    - This effect is **dispelled** on the turn after when the user is attacked.
- Slow:
    - User suffers **-3** Tile Movement.
    - User suffers **-4** Armor Class.
    - User may either perform an **action** *or* a **bonus action** per turn.
    - Negated by **Haste**.
- Stop:
    - User is completely removed from the flow of time, and are unable to do anything.
    - User is **immune** to all incoming effects, attacks/damaging or otherwise, during this.
- Stun:
    - User is **rooted** to their place and unable to move.
    - User fails **Strength** and **Dexterity** saving throws automatically.
    - Attacks made against the user are made with **advantage**.
- Squall:
    - User takes **+2d10** additional fire damage from **any** instance of fire damage dealt to them.
    - **Incoming Wind** typed attacks have **advantage** against the user.
- Toad:
    - User's stats are all reduced by **-6**.
    - User is unable to use **skills, attacks, or reactions.**
    - User has **vulnerability** against **all** incoming damage.
    - Dispels on the user taking damage, immediately.
    - This is counted as a **fully incapacitating effect.**
- Weakness:
    - User loses **-2** on accuracy (to hit) on all **outgoing attack rolls**.
    - User deals **-10** damage on all **outgoing attacks.**
- Wet:
    - User has **resistance** (halved damage) against **Fire** damage.
    - User suffers **+2d12** damage from any instance of **Lightning** damage against them.
    - User has **disadvantage** against saving throws from abilities dealing **Cold** damage.
    - Non-saving throw **incoming attack rolls** dealing **Cold** damage are done at **advantage**.
    - Dispelled by any instances of **Fire** or **Wind** damage.
- Whorl:
    - User has their movement speed **halved**.
    - User is considered **Wet** while this is in effect.
