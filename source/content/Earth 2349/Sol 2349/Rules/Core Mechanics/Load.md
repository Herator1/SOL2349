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

This represents the character’s safe operating capacity under normal conditions.

See [[Base Stats]].

## Current Load

**Current Load** is the amount of active strain a character is carrying at a given moment.

Current Load:

- usually starts at **0**
- increases when implants or certain effects are used
- may rise quickly during combat
- resets during proper recovery

Track **Current Load** and **Maximum Load** separately.

## What Causes Load

The most common causes of Load are:

- activating **[[Implant Overview|implants]]**
- repeated implant or ability use in the same round
- certain **[[Consumables|stims]]**
- special abilities or overdrive effects
- other rules that explicitly generate Load

Load only increases when a rule clearly says it does.

## Repeated Use and Load Scaling

Repeated use of implants and similar systems in the same round increases Load further.

|Use in the Same Round|Additional Load|
|---|---|
|1st|no additional cost|
|2nd|+1 Load|
|3rd|+2 Load|
|4th|+2 Load|
|5th|+3 Load|

This additional Load is applied on top of the normal Load cost of the ability.

### Example

A character uses an implant that normally costs **1 Load**:

- first use: **1 Load**
- second use: **2 Load**
- third use: **3 Load**

## Overload

As long as **Current Load ≤ Maximum Load**, the character suffers no automatic overload effect.

If an action pushes **Current Load above Maximum Load**, the character must immediately check for **Overload** after the action resolves.

The action still happens.

## Overload Trigger

Check for Overload whenever:

- a Load-generating action resolves
- the character’s Current Load is now above Maximum Load

If this happens multiple times in the same round, check Overload each time.

## Overload Value

**Overload Value = Current Load − Maximum Load**

Then roll:

**1d6 + Overload Value**

Apply the result immediately:

|Result|Effect|
|---|---|
|**1–3**|**Minor Glitch** – your next Action suffers **Setback**|
|**4–5**|**System Lag** – lose **1 available Action on your next turn**|
|**6–7**|**Neural Stress** – gain **+1 Mental Condition**|
|**8–9**|**Motor Disruption** – physical actions suffer **Setback** until the end of your next turn|
|**10–11**|**Targeting Glitch** – attacks suffer **Setback** until the end of your next turn|
|**12–13**|**Neural Burn** – take **1d6 Health damage**|
|**14–15**|**System Shock** – gain **+1 Mental Condition** and you cannot activate implants on your next turn|
|**16–17**|**Implant Lock** – the triggering implant cannot be used again this encounter|
|**18–19**|**Critical Feedback** – suffer **1 Wound**|
|**20+**|**Cascade Failure** – suffer **1 Wound** and lose all Actions on your next turn|
## Load in Play

Load creates pressure without becoming a simple resource pool.

It forces choices like:

- use an implant now or save capacity for later
- take a stim now or risk overload later
- stay controlled or push for one decisive turn
- keep acting aggressively or preserve stability

Load should feel like a temptation, not a prohibition.

## Load and Recovery

Current Load is usually a **short-term pressure value**, not a long-term resource.

During a valid [[Rest & Recovery|Short Rest]]:

- reduce Current Load to **0**

During a valid [[Rest & Recovery|Extended Rest]]:

- reduce Current Load to **0**

Unless another rule says otherwise, proper rest fully resets current Load.

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
- [[Implant Overview]]
- [[Rest & Recovery]]
- [[Consumables]]
- [[Character Creation]]
- [[Progression & Advancement]]