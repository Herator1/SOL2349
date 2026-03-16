In Narrative Space Combat, a ship is treated as a single entity with a small set of statistics. These values represent the ship’s overall performance rather than individual subsystems.

Crew actions temporarily modify these statistics during combat. The crew therefore determines how effectively the ship performs in a given situation.

Ships typically use the following statistics.

# Core Ship Statistics

## Thrust

**Thrust** represents the ship’s maneuverability and acceleration.

It determines how well the vessel can change position, evade attacks, and control engagement distance.

Thrust influences:

- Pilot maneuver actions
    
- Evasion against enemy fire
    
- Attempts to change range bands
    
- Alignment for forward-mounted weapons (such as railguns)
    

Typical values:

|Ship Type|Thrust|
|---|---|
|Freighter|1|
|Patrol Boat|3|
|Corvette|3|
|Frigate|2|
|Cruiser|1|

Example uses:

- Pilot rolls may add the ship’s **Thrust** to evasion attempts.
    
- A successful maneuver may grant a **temporary defense bonus**.
    

## Sensors

**Sensors** represent the quality of the ship’s detection, tracking, and targeting systems.

This includes radar, lidar, passive scanning, and electronic warfare support.

Sensors influence:

- Target Lock attempts
    
- Detection of hidden or ambushing ships
    
- Electronic warfare actions
    
- Improving missile Threat values
    

Typical values:

|   |   |
|---|---|
|Ship Type|Sensors|
|Civilian ship|1|
|Patrol vessel|2|
|Military ship|3|

Example uses:

- Sensor operator rolls use **Sensors** as a modifier.
    
- A successful Target Lock can increase missile Threat values.
    


## Armament

**Armament** represents the quality and effectiveness of the ship’s weapon systems.

This statistic applies primarily to **direct fire weapons**, such as railguns or laser arrays.

Armament influences:

- Attack rolls for railguns
    
- Attack rolls for laser weapons
    
- damage potential of some weapon systems
    

Typical values:

|   |   |
|---|---|
|Ship Type|Armament|
|Civilian|0–1|
|Light military|2|
|Warship|3–4|

Example uses:

Attack roll example:

```
d20 + Gunner Skill + Armament
```

This roll is compared against the target’s Defense value.

Guided weapons such as missiles do **not use Armament for attack rolls**, since they automatically track their targets.


## Defense

**Defense** represents the ship’s overall ability to avoid or intercept incoming attacks.

This includes:

- armor
    
- electronic countermeasures
    
- defensive systems
    
- general survivability
    

Defense influences:

- Point Defense rolls against missiles
    
- difficulty of hitting the ship with direct fire weapons
    

Typical values:

|   |   |
|---|---|
|Ship Type|Defense|
|Freighter|1|
|Corvette|2|
|Frigate|3|
|Cruiser|4|

Example use:

Point Defense roll:

```
d20 + Defense + bonuses
```

This roll is compared against the incoming weapon’s Threat value.


## Systems

**Systems** represents the reliability and efficiency of the ship’s internal systems.

This includes:

- reactor stability
    
- power management
    
- computer systems
    
- damage control
    

Systems influences:

- Engineering actions
    
- repairing combat complications
    
- boosting ship systems during combat
    

Typical values:

|   |   |
|---|---|
|Ship Type|Systems|
|Civilian ship|1|
|Military ship|2–3|

Example use:

Engineering roll:

```
d20 + Systems + Engineer Skill
```

Successful engineering actions may restore functionality or grant temporary bonuses.


## Hull Integrity

**Hull Integrity** represents the structural condition of the ship.

This value decreases as the ship takes damage.

When Hull Integrity reaches **0**, the ship becomes **combat ineffective**.

Typical values:

|   |   |
|---|---|
|Ship Type|Hull Integrity|
|Patrol Boat|10|
|Corvette|14|
|Frigate|18|
|Cruiser|24|
|Battleship|30+|

Damage from weapons reduces this value directly.


# Temporary Modifiers

[[Crew Actions and Combat Rounds]]- Crew actions may temporarily modify ship statistics.

Examples:

Pilot Maneuver  
+2 Defense for the round

Sensor Target Lock  
+2 Threat for missiles

Engineering Power Boost  
+1 Armament for the next attack

These bonuses usually last **one combat round**.


# Example Ship

## Warhound-Class Frigate

The Warhound is a small military escort vessel used for patrol and convoy protection.

It is heavily armed for its size and relies on missile strikes and point defense systems.


### Ship Statistics

Warhound-Class Frigate

|   |   |
|---|---|
|Statistic|Value|
|Thrust|2|
|Sensors|3|
|Armament|3|
|Defense|3|
|Systems|2|
|Hull Integrity|18|

Hardpoints: **4**

Typical weapon loadout:

- 2 Missile Racks
    
- 1 Railgun
    
- 1 Gatling Point Defense System
    


### Example Missile Attack

The Warhound launches a missile salvo.

Each missile has:

Threat: **12**

Sensor operator achieves a successful Target Lock.

New Threat:

```
12 + 2 = 14
```

Four missiles are launched.

The defending ship must attempt **Point Defense rolls** against each incoming missile.


# Ship Statistics Summary

|   |   |
|---|---|
|Stat|Used For|
|Thrust|maneuver and evasion|
|Sensors|targeting and electronic warfare|
|Armament|direct weapon attacks|
|Defense|point defense and survivability|
|Systems|engineering and system management|
|Hull Integrity|structural damage capacity|
These statistics allow ships to participate in space combat while keeping the Narrative system fast and easy to use.