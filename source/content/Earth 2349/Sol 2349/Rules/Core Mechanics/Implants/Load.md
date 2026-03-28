Load represents the **short-term strain placed on a character’s body, nervous system, and internal systems** when they push advanced augmentation, stimulants, or other high-performance effects too hard.

It is one of the main limiting mechanics in _SOL 2349_. Load does not usually stop a character from acting, but it makes further system use increasingly dangerous.

## Core Idea

Load is a **pressure resource**.

It reflects:

- neural strain
- biological stress
- interface instability
- system overheating or desynchronization
- the cumulative cost of pushing beyond safe limits

As long as a character stays within their safe Load limit, their systems function normally.

Once they exceed it, they risk **Overload**.

## Maximum Load

Each character has a **Maximum Load**.

**Formula:**  
**Maximum Load = 5 + Intellect**

This value represents the character’s safe operating capacity under normal conditions.

Current Load is tracked separately and rises during play.

See [[Base Stats]].

## Current Load

**Current Load** is the amount of active strain a character is carrying at a given moment.

Current Load:

- usually starts at **0**
- increases when implants or certain effects are used
- may rise quickly during combat
- resets during proper recovery

Track Current Load and Maximum Load separately.

Example:

- Maximum Load: **7**
- Current Load: **4**

The character is operating safely, but has little room left before overload risk begins.

## What Causes Load

The most common causes of Load are:

- activating **[[Implants]]**
- repeated implant or ability use in the same round
- certain **stims**
- special abilities or overdrive effects
- other rules that explicitly generate Load

Load should only increase when a rule clearly says it does.

## Repeated Use and Load Scaling

Repeated use of implants and similar systems in the same round increases Load further.

Use the normal repeated-action scaling:

|Use in the Same Round|Additional Load|
|---|---|
|1st|no additional cost|
|2nd|+1 Load|
|3rd|+2 Load|
|4th|+2 Load|
|5th|+3 Load|

This additional Load is applied on top of the normal Load cost of the ability.

Example:  
A character uses an implant that normally costs **1 Load**.

- first use: **1 Load**
- second use in the same round: **2 Load**
- third use in the same round: **3 Load**

## Safe Load vs Overload

As long as **Current Load ≤ Maximum Load**, the character suffers no automatic overload effect.

If an action pushes **Current Load above Maximum Load**, the character must immediately check for **Overload** after the action resolves.

The action still happens.

This is important:

- Load does not cancel the triggering action
- it makes the consequence come afterward

## Overload Trigger

Check for Overload whenever:

- a Load-generating action resolves
- the character’s Current Load is now above Maximum Load

If this happens multiple times in the same round, check Overload each time.

## Overload Value

**Overload Value = Current Load − Maximum Load**

Then roll:

**1d6 + Overload Value**

Apply the result from the normal [[Implants & Load|Overload table]].

## What Load Does in Play

Load creates pressure without becoming a simple “mana bar.”

It forces choices like:

- use an implant now or save capacity for later
- take a stim now or risk overload later
- stay controlled or push for one decisive turn
- keep acting aggressively or preserve stability

This makes Load one of the main drivers of tactical restraint and burst performance.

## Load and Implants

Implants are the main source of Load.

Implants may:

- cost Load to activate
- generate extra Load when repeated
- create overload risk when pushed too hard
- become unreliable under extreme strain

See [[Implants & Load]] and [[Earth 2349/Sol 2349/Rules/Augmentations and Gear/Implant Overview]].

## Load and Stims

Some **[[Consumables|stims]]** also generate Load.

This represents biological and neurological stress rather than implant activation alone.

A stim that generates Load follows the same basic logic:

- apply the Load when the effect says so
- if this pushes Current Load above Maximum Load, check Overload normally

This means Load is not purely “implant strain,” but a broader measure of high-performance system stress.

## Load and Recovery

Current Load is usually a **short-term pressure value**, not a long-term resource.

### Short Rest

During a valid **[[Rest & Recovery|Short Rest]]**, reduce Current Load to **0**.

### Extended Rest

During a valid **[[Rest & Recovery|Extended Rest]]**, reduce Current Load to **0**.

This reflects:

- cooldown
- neural recovery
- metabolic reset
- implant recalibration
- returning to safe operating state

If the GM wants unusually harsh conditions, they may reduce this recovery, but the normal baseline is a full reset.

## Load During Combat

Load matters most in combat and other high-pressure scenes.

A character with rising Load may still:

- act normally
- attack
- move
- react
- activate more systems

But every additional push risks:

- action penalties
- shutdown
- implant lock
- Health damage
- Wounds
- complete cascade failure

Load should feel like a temptation, not a prohibition.

## Load and Character Identity

Characters with high Intellect can usually support higher Maximum Load, making them better at sustained system use.

This does **not** automatically make them stronger in every situation. It makes them more capable of:

- running advanced systems
- chaining implants safely
- managing high-tech builds
- tolerating enhancement pressure

Load is therefore both a balancing mechanic and a build identity mechanic.

## Example: Safe Use

A character has:

- **Maximum Load 6**
- **Current Load 3**

They activate an implant that costs **2 Load**.

New Current Load: **5**

They remain within safe limits. No overload check is needed.

## Example: Overload Trigger

A character has:

- **Maximum Load 6**
- **Current Load 6**

They use a stim that adds **2 Load**.

New Current Load: **8**

The action resolves. Then they check Overload.

**Overload Value = 8 − 6 = 2**

They roll **1d6 + 2** and apply the result.

## Example: Repeated Implant Use

A character uses the same implant three times in one round. The implant normally costs **1 Load** each time.

- first use: **1 Load**
- second use: **1 + 1 = 2 Load**
- third use: **1 + 2 = 3 Load**

Total Load generated this round: **6**

Even a moderate implant can become dangerous if spammed.

## Summary

- **Maximum Load = 5 + Intellect**
- **Current Load** starts at 0 and rises through use
- implants are the main source of Load
- some stims may also generate Load
- repeated use in the same round increases Load further
- if Current Load rises above Maximum Load, check **Overload**
- the triggering action still resolves
- valid rest normally resets Current Load to 0

## Related Pages

- [[Base Stats]]
- [[Implants & Load]]
- [[Rest & Recovery]]
- [[Consumables]]
- [[Character Creation]]
- [[Progression & Advancement]]