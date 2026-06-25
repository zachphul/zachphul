# Hi, I'm Zachary 👋

I build **AI agents and game tooling** — from an offline computer-vision research
sandbox to a 40-mod Minecraft Fabric library. I like small, well-factored systems
with clean interfaces, real test coverage, and honest documentation.

- 🔭 **Focus:** applied AI (Python / computer vision / behavior-tree agents) and
  developer-friendly game tooling (Java / Fabric).
- 🧩 **Style:** decoupled layers, swappable backends, safety/fair-play by default,
  and READMEs that actually explain the design.
- 🌱 **Currently exploring:** agent architectures and perception pipelines.

---

## 🤖 AI / Computer Vision

| Project | What it is | Stack |
|---------|-----------|-------|
| **[brawler-arena-sandbox](https://github.com/zachphul/brawler-arena-sandbox)** | An **offline AI research sandbox**: a Pygame arena driven by a decoupled perceive → decide → act agent — a **YOLOv8 + OCR** vision pipeline, a **py_trees** behavior tree, and **Bézier-curve** kinematics, all behind a swappable driver HAL. No real game, no emulator, no networking — a pure simulation target for agent research. | Python · Ultralytics · py_trees |

## 🎮 Minecraft / Fabric

| Project | What it is | Stack |
|---------|-----------|-------|
| **[minecraft-fabric-mods](https://github.com/zachphul/minecraft-fabric-mods)** | A library of **39 lightweight, client-side QoL / HUD / utility mods** for MC 1.21.x — each a self-contained Gradle project, configurable via Mod Menu + YACL. | Java 21 · Fabric · Gradle |
| **[SkyZen](https://github.com/zachphul/SkyZen)** | An all-in-one **SkyBlock QoL suite** (SkyHanni / Skytils-style): skill & coin trackers, slayer/fishing/dungeon HUDs, event timers, chat cleaner, and price tooltips. | Java 21 · Fabric · Mixins |
| **[BazaarFlip](https://github.com/zachphul/BazaarFlip)** | Live **Hypixel SkyBlock bazaar flip calculator**: purse-aware orders, a craft-flip profit engine, and NPC arbitrage on one clean overlay. Ships across 1.21.10 / 1.21.11 + Lite variants + a 1.8.9 Forge port. | Java · Fabric / Forge |

---

## 🛠️ Tech

**Languages:** Python · Java
**AI / CV:** Ultralytics YOLOv8 · EasyOCR · py_trees · NumPy · Pygame
**Game modding:** Fabric · Mixins · Gradle · YACL · Mod Menu · Forge
**Tooling:** Git · Poetry · pytest
