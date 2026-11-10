---
layout: default
title: Server Systems
permalink: /systems/
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
