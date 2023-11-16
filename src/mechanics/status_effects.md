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
- Bleed:
- Blind:
- Break:
- Burn:
- Curse:
- Doom:
- Frostbite:
- Heavy:
- Paralyze:
- Poison:
- Resurrection Sickness
    - Prevents resurrection until expired / cured.
- Silence:
- Sleep:
- Slow:
- Stop:
- Stun:
- Squall:
- Toad:
- Weakness:
- Wet:
- Whorl:
