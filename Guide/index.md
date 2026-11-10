---
layout: default
title: PowerCoreSMP Player Guide
---

<a id="quick-start"></a>

## 🚀 Quick Start

```
 1.  Join the server          →  You receive a Charged Core automatically
 2.  Kill mobs                →  Collect Fragments for your desired core
 3.  Craft a Power Core       →  Fragments + Charged Core at a crafting table
 4.  /core-equip              →  Moves core to your offhand
 5.  Select hotbar slot       →  SHIFT + RIGHT CLICK to use abilities!
```

> **Tip:** Use `/core-recipe` to see all crafting recipes in-game.

---

<a id="core-lifecycle"></a>

## 🔄 Core Lifecycle

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  Charged     │────▶│  Power      │────▶│  Die 3x/5x  │────▶│  Fused      │
│  Core        │     │  Core       │     │  (hearts ↓)  │     │  Core       │
└─────────────┘     └─────────────┘     └─────────────┘     └──────┬──────┘
       ▲                                                           │
       └───────────────────────────────────────────────────────────┘
                          Receive new Charged Core
```

| Stage | Description |
|:------|:------------|
| **Charged Core** | Starting item. Required ingredient to craft any Power Core. |
| **Power Core** | Your active core — grants abilities and passive effects. |
| **Fused Core** | Core becomes inert after too many deaths. You start over with a new Charged Core. |

### Ownership Rules

> - `1` core per player
> - `2` players max per standard core type
> - `1` player max per dimensional core type

---

<a id="how-to-use-abilities"></a>

## 🎮 How to Use Abilities

| Step | Action |
|:----:|:-------|
| **1** | Have a Power Core in your inventory |
| **2** | Run `/core-equip` — it moves to your offhand |
| **3** | Hotbar slots `1-5` (or `1-7` for dimensional) are bound to abilities |
| **4** | Select the hotbar slot for the ability you want |
| **5** | **`SHIFT` + `RIGHT CLICK`** to activate |

> While equipped in your offhand, you also passively gain effects unique to your core type.

---

<a id="keybinds"></a>

## ⌨️ Keybinds

Each core comes with default ability bindings. Customize them anytime:

```
/core-bind <ability> <slot>    Bind an ability to hotbar slot 1-5 (1-7 dimensional)
/core-unbind <slot>            Remove a binding from a slot
/core-bindreset                Reset all bindings back to defaults
/core-actionbar                Toggle the cooldown display above your hotbar
```

---

<a id="standard-cores"></a>

## 🛡️ Standard Cores

> Standard cores have **5 abilities** and **fuse after 3 deaths**.

---

<a id="fire-core"></a>

### 🔥 Fire Core

> **Passives:** Fire Resistance · +10% melee damage · Burn attackers on hit

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Fireball** | `10s` | 8 HP | Explosive projectile, sets targets on fire for 5s |
| **Flame Aura** | `35s` | 3 HP/s | Burning aura for 15s (5-block radius) |
| **Flame Wave** | `20s` | 1 HP/tick | Continuous fire wave following your aim for 5s |
| **Phoenix Dash** | `15s` | 10 HP | Dash forward with AOE damage + 10s fall immunity |
| **Volcanic Eruption** | `35s` | 18 HP | Targeted ground explosion (25-range, 6-radius) |

> **Fragments from:** Blaze (20%)

---

<a id="ice-core"></a>

### ❄️ Ice Core

> **Passives:** Slowness immunity · Freeze nearby blocks (5-block radius) · Slow attackers on hit

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Blizzard** | `20s` | 14 HP | Instant snowstorm (12-radius), Slowness IV for 8s |
| **Frost Aura** | `30s` | 3 HP/s | Freezing aura for 15s (6-radius), Slowness III |
| **Frost Nova** | `25s` | 14 HP | Instant freeze burst (5-radius), Slowness III for 5s |
| **Glacial Spike** | `30s` | 16 HP | Single-target ice spike (20-range), launches enemy up |
| **Icicle Barrage** | `15s` | 2 HP ×5 | 5 rapid icicles, Slowness I |

> **Fragments from:** Stray (20%) · Polar Bear (30%)

---

<a id="void-core"></a>

### 🟣 Void Core

> **Passives:** Night Vision · Invisible when sneaking · Teleport backward when hit · -20% fall damage

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Darkness Aura** | `40s` | 4 HP | Darkness field for 25s (10-radius) |
| **Void Collapse** | `50s` | 22 HP | Powerful single-target implosion (15-range) |
| **Void Echo** | `35s` | 14 HP | Echoes damage between targets for 20s (10-radius) |
| **Void Rift** | `60s` | 22 HP | AOE void tear (10-radius) |
| **Void Step** | `12s` | 8 HP | Short teleport with AOE on arrival (20-range) |

> **Fragments from:** Enderman (20%)

---

<a id="nature-core"></a>

### 🌿 Nature Core

> **Passives:** Regeneration I · +1 extra heart · Auto-heal below 50% HP

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Forest's Wrath** | `45s` | 18 HP | AOE nature damage (10-radius) |
| **Life Surge** | `30s` | — | Full health restore + removes negative effects |
| **Nature's Blessing** | `45s` | — | Healing/protection buff for 20s |
| **Thorn Shield** | `50s` | 75% reflect | Reflects 75% incoming damage for 15s |
| **Vine Whip** | `15s` | 10 HP | Ranged whip attack (15-range) |

> **Fragments from:** Chicken (20%) · Sheep (15%) · Cow (10%) · Pig (10%)

---

<a id="storm-core"></a>

### ⚡ Storm Core

> **Passives:** Speed I · Lightning counter-attack · Knockback immunity · Lightning immunity

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Lightning Spear** | `25s` | 14 HP | Long-range lightning projectile (25-range) |
| **Lightning Strike** | `15s` | 10 HP | Instant strike (3-radius) |
| **Static Field** | `20s` | 3 HP/s | Electric damage zone for 10s (8-radius) |
| **Storm Surge** | `30s` | 16 HP | Charged AOE blast — 3s charge time (15-radius) |
| **Thunder Dash** | `18s` | 10 HP | Lightning dash with AOE on impact (5-radius) |

> **Fragments from:** Creeper (20%) · Charged Creeper (80%)

---

<a id="lunar-core"></a>

### 🌙 Lunar Core

> **Passives:** Night Vision · Jump Boost II at night · +50% damage at night · Slow Falling below 30% HP

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Cosmic Ray** | `18s` | 12 HP | Cosmic beam attack (20-range) |
| **Eclipse** | `75s` | — | Powerful buff ability for 20s |
| **Lunar Leap** | `20s` | 10+10 HP | Damage on launch and landing (10-radius) |
| **Moon Gravity** | `45s` | — | Gravity manipulation for 15s (12-radius) |
| **Starfall** | `35s` | 4 HP ×20 | 20 meteors rain from sky over 10s |

> **Fragments from:** Phantom (70%)

---

<a id="blood-core"></a>

### 🩸 Blood Core

> **Passives:** Absorption I · Heal 2 HP on kill · 20% lifesteal · Regen below 30% HP

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Bat Shroud** | `45s` | — | 15-20 bats each absorb 1 hit for 20s |
| **Blood Mist** | `20s` | 14 HP | Crimson mist (8-radius), heals 2 HP per enemy |
| **Blood Pact** | `45s` | — | Sacrifice 10 HP → Speed III, Str III, Regen I, Res I (20s) |
| **Crimson Chains** | `35s` | 14+3/s+6 | Root all enemies (8-radius, 4s), damage on root/during/break |
| **Life Drain** | `20s` | 14 HP | Single-target drain (20-range), heals 4 HP |

> **Fragments from:** Bat (90%)

---

<a id="crystal-core"></a>

### 💎 Crystal Core

> **Passives:** Absorption II · 15% damage reflection · +10% all damage

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Crystal Storm** | `30s` | 10 HP ×15 | 15 crystal shards rain from sky over 5s |
| **Mirror Shield** | `60s` | 100% reflect | Total damage reflection for 5s — take 0 damage |
| **Prismatic Blast** | `20s` | 14 HP | Rainbow beam pierces enemies, random debuff |
| **Radiant Aura** | `30s` | 5 dmg / 2 heal /s | Damages enemies + heals you for 10s (5-radius) |
| **Refract** | `25s` | — | Redirects incoming projectiles for 8s (8-radius) |

> **Fragments from:** Amethyst Cluster (20%)

---

<a id="ocean-core"></a>

### 🌊 Ocean Core

> **Passives:** Water Breathing · Dolphin's Grace · +30% trident damage

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Hydro Pump** | `25s` | 14 HP | Water projectile (20-range) |
| **Pressure Zone** | `35s` | 3 HP/s | High-pressure water zone for 10s (7-radius) |
| **Riptide Strike** | `15s` | 10 HP | Water dash with AOE impact (15-range, 5-radius) |
| **Tidal Blessing** | `40s` | — | Water-based protection buff for 20s |
| **Tsunami** | `70s` | 24 HP | Massive wave (20-range, 15-width) |

> **Fragments from:** Guardian (30%) · Drowned (20%)

---

<a id="undead-core"></a>

### 💀 Undead Core

> **Passives:** Poison/Hunger immunity · Night Vision · +4 HP on kill · Undead mobs won't attack you

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Army of Dead** | `35s` | — | Summons 4 zombies + 4 skeletons for 60s |
| **Bone Shield** | `40s` | 75% reflect | Absorbs 3 hits or lasts 10s, reflects 75% damage |
| **Contagion** | `15s` | 8+2/s | Poison that spreads to nearby enemies (5-block spread) |
| **Flesh Hook** | `25s` | 6 HP | Hooks and roots enemy for 3s (20-range) |
| **Rotting Ground** | `30s` | 3 HP/s | Toxic zone around you for 12s (6-radius) |

> **Fragments from:** Zombie (10%) · Skeleton (10%) · Wither Skeleton (15%) · Zombie Villager (20%) · Husk (10%)

---

<a id="dimensional-cores"></a>

## 🌌 Dimensional Cores

> Dimensional cores are **rare, powerful, and exclusive**. They have **7 abilities** and **fuse after 5 deaths**. Only **1 player** can own each type.

---

<a id="dragon-core"></a>

### 🐉 Dragon Core

> **Passives:** End Presence (particles) · Void Ascendance (saved from void death) · Dragon's Dominance (all mobs passive)

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Draconic Onslaught** | `1 hour` | 7 HP | 10s empowered dragon form |
| **End Static** | `10 min` | — | Disables ALL abilities in 50-radius for 60s |
| **Abyssal Storm** | `45s` | 1.5 HP ×2/s | Rapid strikes for 5s (15-radius) |
| **Dragon's Roar** | `45s` | 9 HP | 90° cone attack (50-range), massive knockback |
| **Void Wings** | `2 min` | — | Flight for 20 seconds |
| **Ender Blessing** | `5 min` | — | Protective buff (10-radius) for 30s |
| **Void Warp** | `48 hours` | — | Long-range teleportation |

> **How to Obtain:** Essence Shards (Ender Dragon) + Divine Catalyst (100% dragon drop)

---

<a id="soul-core"></a>

### 👻 Soul Core

> **Passives:** Nether Presence (particles) · Terror Aura (mobs flee) · Void Resistance

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Soul Army** | `1 hour` | — | Summons 3 soul withers for 60s |
| **Nether Corruption** | `48 hours` | — | 12s charge, corrupts 10-radius |
| **Decay Aura** | `2 min` | — | Decay field (10-radius) for 30s |
| **Soul Harvest** | `5 min` | 8 HP | Harvests souls (10-radius) for 5s |
| **Soul Wings** | `2 min` | — | Flight for 20 seconds |
| **Death Ray** | `1 hour` | Instant Kill | Execution — target must have 2+ deaths |
| **Soul Abduction** | `48 hours` | — | Soul-stealing ultimate |

> **How to Obtain:** Essence Shards (Wither) + Soul of Wither (30% wither drop)

---

<a id="ancient-core"></a>

### 🏛️ Ancient Core

> **Passives:** Sculk Presence (particles) · Void Bargain (lose hearts instead of dying) · Ominous Presence (boss bar)

| Ability | Cooldown | Damage | Description |
|:--------|:--------:|:------:|:------------|
| **Ancient Call** | `20 min` | — | Summons a Warden ally for 5 minutes |
| **Sculk Resonance** | `1 hour` | 2× multiplier | Doubles all damage for 60s (15-radius) |
| **Vitality Surge** | `10 min` | 2× heal | Doubles healing (50-radius) for 60s |
| **Sonic Boom** | `1 hour` | 9 HP beam | Stuns all enemies (10-radius) for 5s |
| **Sculk Wings** | `10 min` | — | Flight for 60s + 2× speed + darkness aura |
| **Echo Barrage** | `1 hour` | — | Fires 1000 arrows over 10 seconds |
| **Soul Shriek** | `3 days` | −3 hearts | Permanently removes 3 max hearts from target |

> **How to Obtain:** Warden Heart (20% warden drop) + special materials

---

<a id="crafting--fragments"></a>

## ⚒️ Crafting & Fragments

### How Fragments Work

Kill specific mobs to collect fragments → combine with a Charged Core to craft your Power Core.

```
  Mob Kill  ──▶  Fragment Drop  ──▶  Collect Enough  ──▶  Craft Power Core
```

> Use `/core-recipe` in-game to see exact recipes and required materials.

### Fragment Drop Sources

| Core | Mob | Drop Rate |
|:-----|:----|:---------:|
| Fire | Blaze | 20% |
| Ice | Stray | 20% |
| Ice | Polar Bear | 30% |
| Void | Enderman | 20% |
| Nature | Chicken | 20% |
| Nature | Sheep | 15% |
| Nature | Cow | 10% |
| Nature | Pig | 10% |
| Storm | Creeper | 20% |
| Storm | Charged Creeper | 80% |
| Lunar | Phantom | 70% |
| Blood | Bat | 90% |
| Crystal | Amethyst Cluster | 20% |
| Ocean | Guardian | 30% |
| Ocean | Drowned | 20% |
| Undead | Zombie | 10% |
| Undead | Skeleton | 10% |
| Undead | Wither Skeleton | 15% |
| Undead | Zombie Villager | 20% |
| Undead | Husk | 10% |

### Boss Material Drops

| Boss | Drop | Chance |
|:-----|:-----|:------:|
| Ender Dragon | Essence Shards (2-4) | `100%` |
| Ender Dragon | Divine Catalyst | `100%` |
| Wither | Essence Shards (2-4) | `100%` |
| Wither | Soul of Wither | `30%` |
| Warden | Warden Heart | `20%` |
| Elder Guardian | Essence Shard | `50%` |

### Gems

Gems spawn in naturally generated loot chests throughout the world.

| Property | Value |
|:---------|:------|
| Chest spawn chance | 70% |
| Per-color chance | 30% |
| Amount per color | 1-10 |
| Colors | Red, Orange, Yellow, Lime, Cyan, Blue, Purple, Pink, White, Brown |

> Gems are used for **Rituals** — collect all 10 colors to restore lost hearts.

---

<a id="ritual-system"></a>

## 🔮 Ritual System

Rituals restore your max hearts lost from deaths.

### How to Perform a Ritual

```
  1.  Collect 10 unique gem colors (one of each)
  2.  Have enough XP levels
  3.  Run /core-ritual normal  or  /core-ritual boosted
```

### Ritual Types

| Type | XP Cost | Requirements | Hearts Restored |
|:-----|:-------:|:-------------|:---------------:|
| **Normal** | 30 levels | 10 unique gems | 1 heart (2 HP) |
| **Boosted** | 70 levels | 10 unique gems + 10+ max hearts | 1 heart + bonus |

---

<a id="trading"></a>

## 🤝 Trading

Trade your Power Core with another player.

### How to Trade

```
  You:    /core-trade send <player>     Send a trade request
  Them:   /core-trade accept            Accept the trade
          /core-trade deny              Deny the trade
```

### Rules

> - Both players must have active Power Cores
> - Cores must be **different types**
> - Request expires after **60 seconds**
> - **12-hour cooldown** between trades

---

<a id="altars"></a>

## 🏛️ Altars

Altars are rare structures that spawn naturally as you explore.

| Property | Value |
|:---------|:------|
| Spawn rate | 0.3% per chunk |
| Location bias | 70% near villages (30-60 blocks) |
| Min distance apart | 300 blocks |
| Height range | Y 50-120 |
| Boss bar range | 100 blocks |
| Entry trigger | 10 blocks |
| Use cooldown | 1 hour |

> Walk within 10 blocks of an altar to see its boss bar. Used for obtaining cores and performing rituals.

---

<a id="death--fusing"></a>

## 💀 Death & Fusing

### How Death Affects Your Core

| Event | Effect |
|:------|:-------|
| Each death | Lose **1 heart** (2 HP) of max health |
| Standard core — 3 deaths | Core **fuses** (becomes inert) |
| Dimensional core — 5 deaths | Core **fuses** (becomes inert) |
| Core fuses | You receive a new **Charged Core** |
| Minimum health | **10 hearts** (20 HP) — can never go below |

### Recovering Hearts

> Perform **Rituals** to restore lost max hearts. Each ritual restores 1 heart.

---

<a id="commands"></a>

## 📝 Commands

### Player Commands

```
/core-equip                     Equip your core to offhand
/core-stats                     View core info, keybinds, kill/death stats
/core-recipe                    Open crafting recipe book
/core-preview <core>            Preview a core's abilities
/core-ritual                    Open ritual GUI
/core-bind <ability> <slot>     Bind ability to hotbar slot
/core-unbind <slot>             Remove a keybind
/core-bindreset                 Reset keybinds to defaults
/core-actionbar                 Toggle cooldown display
/core-trade send <player>       Send trade request
/core-trade accept              Accept pending trade
/core-trade deny                Deny pending trade
/core-help                      Show help menu
```

### Short Aliases

> Every command works without the `core-` prefix too:
> `/equip`, `/stats`, `/recipe`, `/preview`, `/ritual`, `/bind`, `/unbind`, `/bindreset`, `/actionbar`, `/trade`, `/help`

---

<a id="tips--tricks"></a>

## 💡 Tips & Tricks

### Combat

- **Lunar Core** deals +50% damage at night with Jump Boost II — fight after dark
- **Blood Core** excels in sustained fights with 20% lifesteal + kill healing
- **Crystal Core's Mirror Shield** reflects 100% damage — bait enemies into attacking
- **Storm Core** has knockback immunity — hold positions without being pushed
- **Nature Core's Life Surge** instantly restores full HP — the best panic button

### Exploration

- **Void Core** turns invisible while sneaking — perfect for stealth
- **Ocean Core** dominates underwater with Water Breathing + Dolphin's Grace
- **Dragon Core's Void Wings** gives 20s flight on a 2 min cooldown
- **Ancient Core's Sculk Wings** provides 60s flight + 2x speed

### Farming

- Farm **Phantoms** for Lunar fragments — **70% drop rate** (highest standard)
- Farm **Bats** for Blood fragments — **90% drop rate** (highest overall)
- **Charged Creepers** drop Storm fragments at **80%** — use channeling trident
- Always stock up on **gems** for rituals to recover lost hearts

### Strategic

- **Undead Core** minions persist even if you disconnect and rejoin
- Dimensional cores are rarer but survive **5 deaths** instead of 3
- **Ancient Core's Soul Shriek** permanently removes hearts — use wisely (3-day cooldown)
- **End Static** disables ALL abilities in 50 blocks — including yours and your team's
