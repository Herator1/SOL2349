In space combat, a ship is treated as a single combat entity with a small set of core statistics. These values represent the vessel’s overall performance rather than every subsystem in technical detail.

Crew actions temporarily improve, protect, or stabilize these values during combat. The ship therefore performs well only if its crew keeps it operating effectively under pressure.

## Core Ship Statistics

## Thrust

**Thrust** represents the ship’s acceleration, maneuverability, and ability to change position under combat conditions.

It influences:
- changing **Range Bands**
- evasive maneuvering
- alignment for forward-facing weapons
- pursuit, withdrawal, and interception positioning

Typical values:

| Ship Type | Thrust |
|---|---:|
| Freighter | 1 |
| Patrol Boat | 3 |
| Corvette | 3 |
| Frigate | 2 |
| Cruiser | 1 |
Higher **Thrust** means the ship is better at controlling distance and angle.

---
## Sensors

**Sensors** represent the ship’s ability to detect, identify, track, and interpret targets or environmental conditions.

They influence:
- target locks
- hidden ship detection
- electronic warfare
- scan actions
- missile and guided-weapon support

Typical values:

| Ship Type | Sensors |
|---|---:|
| Civilian Ship | 1 |
| Patrol Vessel | 2 |
| Military Ship | 3 |
Higher **Sensors** make it easier to control information and create firing opportunities.

---

## Defense

**Defense** represents how hard the ship is to hit with direct fire.

It includes:
- evasive profile
- flight handling under pressure
- thermal and radar discipline
- target complexity
- onboard defensive positioning

Direct-fire attacks target:

**Base DC 10 + Defense**

Typical values:

| Ship Type | Defense |
|---|---:|
| Freighter | 1 |
| Corvette | 2 |
| Frigate | 3 |
| Cruiser | 4 |

A ship with **Defense 3** is therefore attacked at **DC 13** before other effects apply.


---

## Point Defense

**Point Defense** represents the ship’s ability to intercept incoming missiles, torpedoes, drones, and similar guided threats.

It includes:
- defensive guns
- interceptor systems
- tracking logic
- close-in defensive coverage

Point Defense is used for **interception rolls**.

Typical values:

| Ship Type | Point Defense |
|---|---:|
| Civilian Ship | 0–1 |
| Patrol Vessel | 2 |
| Warship | 3–4 |

A Point Defense roll is usually:

**1d20 + Point Defense**

Crew actions may improve this further.


---

## Systems

**Systems** represents the reliability, flexibility, and recoverability of the ship’s internal systems.

It includes:
- power routing
- reactor stability
- internal control systems
- damage control
- engineering resilience

Systems influence:
- engineering support
- system recovery
- emergency rerouting
- keeping damaged functions online

Typical values:

| Ship Type | Systems |
|---|---:|
| Civilian Ship | 1 |
| Military Ship | 2–3 |

Higher **Systems** make a ship easier to stabilize and harder to fully cripple.


---

## Hull Integrity

**Hull Integrity** represents the structural condition and remaining combat viability of the ship.

This value is reduced by incoming damage.

When **Hull Integrity** reaches **0**, the ship becomes **combat ineffective**.

Typical values:

| Ship Type | Hull Integrity |
|---|---:|
| Patrol Boat | 10 |
| Corvette | 14 |
| Frigate | 18 |
| Cruiser | 24 |
| Battleship | 30+ |
A ship at **0 Hull Integrity** is no longer combat-capable, but may still be:
- drifting
- venting
- powerless
- boardable
- salvageable

This does not always mean immediate total destruction.

---

## Weapon Systems

Weapons are not a universal ship statistic.  
Each ship carries specific weapon systems with their own profiles, such as:
- railguns
- laser arrays
- missile racks
- torpedo tubes
- point-defense batteries

This keeps ship combat simpler and avoids a second “attack stat” layered on top of crew skill.

See [[Weapons]].

---

## Temporary Effects

[[Crew Actions and Combat Rounds]] may temporarily improve or hinder ship performance.

Typical examples:
- improved position for direct fire
- better target lock
- degraded incoming missile tracking
- temporary system restoration
- stronger point-defense response
- reduced enemy firing advantage

As a rule:
- short-term effects usually last until the **end of the round**
- or until the **next relevant action** is resolved

Use the strongest relevant effect rather than stacking too many small bonuses.

---

## Example Ship

## Warhound-Class Frigate

The **Warhound** is a small military escort vessel used for patrol and convoy protection.

It is heavily armed for its size and relies on missiles, point defense, and disciplined crew coordination.

### Ship Statistics

| Statistic | Value |
|---|---:|
| **Thrust** | 2 |
| **Sensors** | 3 |
| **Defense** | 3 |
| **Point Defense** | 3 |
| **Systems** | 2 |
| **Hull Integrity** | 18 |

**Hardpoints:** 4

Typical loadout:
- 2 Missile Racks
- 1 Railgun
- 1 Gatling Point-Defense System

### Example Direct-Fire Target Number

A Warhound-Class Frigate has **Defense 3**.

A direct-fire attack against it targets:

**Base DC 10 + 3 = DC 13**

before other effects such as evasive maneuvering or sensor support.

### Example Missile Interception

A hostile missile salvo creates an incoming **Threat 14**.

The Warhound attempts interception with:

**1d20 + Point Defense**

Its **Point Defense** is **3**, so the roll is:

**1d20 + 3**

Crew actions may improve this further.

---

## Ship Statistics Summary

| Stat | Used For |
|---|---|
| **Thrust** | maneuvering, range control, pursuit, evasion setup |
| **Sensors** | lock, scan, detection, electronic warfare |
| **Defense** | direct-fire target difficulty |
| **Point Defense** | intercepting guided weapons |
| **Systems** | engineering, recovery, system support |
| **Hull Integrity** | structural damage capacity |

These statistics keep space combat readable while preserving the core feel of crew-driven ship combat.