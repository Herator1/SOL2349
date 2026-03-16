Point Defense systems (PD) protect a ship from incoming guided weapons such as **torpedoes, missiles, and light missiles**. These systems use rapid-fire cannons, interceptor rockets, or defensive lasers to destroy incoming threats before they reach the hull.

In Narrative Space Combat, Point Defense is an **active defense system**. When missiles are launched, the defending ship attempts to intercept them using its available PD systems.

# Point Defense Systems

Each Point Defense weapon occupies one **Hardpoint** on the ship.

Typical PD systems include:

- **Gatling PD Cannons** (rapid kinetic interceptors)
    
- **Defensive Laser Arrays**
    
- **Interceptor Pod Launchers**
    

Different PD types may exist in the setting, but they all follow the same basic rules in Narrative Combat.

# Maximum Shots per Round

Each PD system can fire a limited number of times per combat round.

Example:

**Gatling Point Defense System**

Maximum: **4 shots per round**

Each additional shot suffers a cumulative penalty due to tracking difficulty, heat buildup, and target saturation.

|Shot Number|Modifier|
|---|---|
|1|0|
|2|−4|
|3|−8|
|4|−12|

Once a PD system has used all of its shots, it cannot fire again until the next round.

# Intercepting Missiles

Missiles are resolved **one at a time**.

For each incoming missile:

1. A Point Defense system may attempt an interception roll.
    
2. If the attempt fails, another PD system may attempt to intercept.
    
3. Continue until:
    
    - the missile is destroyed, or
        
    - all available PD systems have fired.
        

Each PD system tracks its own number of shots used during the round.

# Point Defense Roll

To intercept a missile, roll:

```
d20 + Defense + situational bonuses
```

Situational bonuses may include:

- Pilot maneuver actions
    
- Sensor support
    
- engineering assistance
    

The final result is compared to the missile's **Threat Value**.


# Interception Results

### Intercept

If the roll **equals or exceeds the Threat Value**, the missile is destroyed.

No damage is applied.

### Near Hit

If all interception attempts fail, but the **best failed roll is greater than half the Threat**, the missile detonates near the ship.

The ship takes **reduced damage**.

### Direct Hit

If the best failed roll is **equal to or less than half the Threat**, the missile strikes the ship directly.

The ship takes **full damage**.

---

# Example 1 – Single Missile Interception

A frigate launches a missile with:

Threat: **12**

The defending corvette attempts interception.

Defense: **3**

The player rolls:

```
d20 = 9
9 + 3 = 12
```

Result:

12 ≥ 12 → **Intercept**

The missile is destroyed before reaching the ship.

---

# Example 2 – Failed Interception (Near Hit)

Threat: **14**

Point Defense roll:

```
d20 = 9
9 + 3 = 12
```

12 is less than the Threat value, so the interception fails.

Half the Threat is **7**.

12 > 7 → **Near Hit**

The missile detonates close to the ship.

Damage is applied using the weapon's **Near Hit damage value**.

---

# Example 3 – Direct Hit

Threat: **14**

Point Defense roll:

```
d20 = 3
3 + 3 = 6
```

6 ≤ 7 (half the Threat)

Result:

**Direct Hit**

The missile impacts the hull and deals full damage.

---

# Example 4 – Multiple Point Defense Systems

A ship has:

- **2 Gatling PD systems**
    
- each can fire **4 times per round**
    

Four missiles are incoming.

Missile Threat: **14**

Defense bonus: **+4**

---

### Missile 1

PD System A fires:

```
d20 = 10
10 + 4 = 14
```

Intercept successful.

Missile destroyed.

---

### Missile 2

PD System A fires again (second shot, −4 penalty):

```
d20 = 11
11 + 4 − 4 = 11
```

Miss.

PD System B fires:

```
d20 = 12
12 + 4 = 16
```

Intercept successful.

---

### Missile 3

PD System A fires (third shot, −8 penalty):

```
d20 = 14
14 + 4 − 8 = 10
```

Miss.

PD System B fires (second shot, −4 penalty):

```
d20 = 8
8 + 4 − 4 = 8
```

Miss.

Best failed roll: **10**

10 > 7 → **Near Hit**

Reduced damage is applied.

---

### Missile 4

PD System A fires (fourth shot, −12 penalty):

```
d20 = 7
7 + 4 − 12 = −1
```

Miss.

PD System B fires (third shot, −8 penalty):

```
d20 = 5
5 + 4 − 8 = 1
```

Miss.

Best failed roll: **1**

1 ≤ 7 → **Direct Hit**

Full damage is applied.

---

# Tactical Notes

Point Defense is most effective when:

- multiple PD systems are installed
    
- crew support actions improve Defense
    
- missile salvos are intercepted early
    

Large missile salvos can overwhelm Point Defense by forcing multiple interception attempts in a single round.