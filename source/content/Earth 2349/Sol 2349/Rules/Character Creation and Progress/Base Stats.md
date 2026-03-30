# Base Stats

Base Stats define a character’s **survivability, system limits, and build capacity**. Unlike [[Attributes]] and [[Skills]], they determine **how long you last, how much punishment you can absorb, and how far you can push your systems**.

Most Base Stats are derived from attributes, equipment, or fixed character values. Some may later be improved through gear, implants, or advancement.

## Guard

**Guard** represents a character’s immediate combat buffer: mobility, reactions, resilience under pressure, and protective equipment all working together to prevent real injury.

Damage is applied to **Guard first**.

**Formula:**  
**Guard = Reflexes + Fitness + Armor**

### Characteristics

- dynamic during combat
- depleted before Health
- may be restored through actions or effects
- lost quickly under sustained pressure

Guard determines how long a character can avoid taking real bodily harm.

## Health

**Health** represents physical condition, endurance, and the ability to keep functioning after injury.

Damage is applied to **Health** once Guard is depleted.

**Formula:**  
**Health = 8 + (2 × Fitness)**

### Characteristics

- reflects actual injury
- more stable than Guard
- recovers through rest or treatment

Health determines how long a character can remain functional once combat control breaks down.

## Wounds

**Wounds** represent critical trauma and lasting injury.

A character suffers a Wound when their **Health drops below 0**.

**Base Value:**  
**Maximum Wounds = 3**

### Characteristics

- each Wound causes penalties and temporary collapse
- Wounds accumulate over time
- reaching maximum Wounds causes the character to enter the **Dying** state

Wounds define how close a character is to total incapacitation and death.

## Load

**Load** measures the strain placed on the body and implanted systems by augmentation use.

In play, current Load rises and falls. The value below defines a character’s **maximum safe Load**.

**Formula:**  
**Maximum Load = 5 + Intellect**

### Characteristics

- implant use increases current Load
- exceeding maximum Load triggers an Overload check (see [[Load]])
- Load does not prevent action by itself, but makes further use increasingly risky

Maximum Load is the core limiter for implant-heavy characters.

## Mod Space

**Mod Space** represents long-term implant capacity.

Each implant consumes part of this capacity.

**Base Value:**  
**Mod Space = 5**

### Characteristics

- each implant uses Mod Space
- this is a hard limit unless another rule increases it
- it shapes long-term build choices rather than round-to-round combat decisions

Mod Space defines how extensively a character can be augmented.

# Summary

- **Reflexes + Fitness + Armor → Guard**
- **Fitness → Health**
- **Intellect → Maximum Load**
- **Maximum Wounds = 3**
- **Mod Space = 5**
- **Implants create pressure through Load and Mod Space**