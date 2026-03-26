# 🧬 Base Stats

Base Stats define a character’s **survivability and system limits**.  
Unlike attributes and skills, they determine **how long you last, how much you can take, and how far you can push your systems**.

They are **derived from attributes and equipment**, but can also be improved directly.

---
## 🛡️ Guard

Represents **immediate survivability** (movement, reactions, positioning).  
Damage is applied to Guard first.

**Base Formula:**

Guard = Reflexes + Fitness + Armor

**Characteristics:**

- dynamic (changes during combat)
- restored through actions (e.g. Take Cover)
- lost quickly under pressure

👉 determines how long you avoid real damage

---
## ❤️ Health

Represents **physical condition and endurance**.  
Damage is applied to Health once Guard is depleted.

**Base Formula:**

Health = 8 + (2 × Fitness)

**Characteristics:**

- reflects actual injury
- recovers through rest or treatment

👉 determines how long you stay functional

---
## 🩸 Wounds

Represents **critical injuries**.

**Trigger:**

- Health drops below **0**

**Base Value:**

Wounds = 3 (default, can be increased)

**Effects:**

- temporary incapacitation
- cumulative penalties

👉 defines when a character becomes **dying**

---
## 🔥 Load

Represents **system strain from implants and abilities**.

**Base Formula:**

Load = 5 + Intellect

**Characteristics:**

- increases during use of implants
- exceeding max → **Overload Roll**
- does not block actions, but makes them risky

👉 core limiter for augmentation-heavy builds

---
## 🧠 Stress

Represents **mental pressure and stability**.

**Base Formula:**

Stress = 5 + Presence

**Characteristics:**

- increases through danger, fear, overload
- exceeding threshold triggers **Stress Reaction**

👉 limits psychological endurance

---
## 🧬 Mod Space

Represents **implant capacity**.

**Base Value:**

Mod Space = 5 (default, can be increased)

**Characteristics:**

- each implant consumes space
- hard limit for build design

👉 defines long-term character configuration

---
# 🎯 Summary

- **Reflexes + Fitness → Guard**
- **Fitness → Health**
- **Intellect → Load**
- **Presence → Stress**
- **Equipment → Guard (Armor)**
- **Implants → Load + Mod Space pressure**