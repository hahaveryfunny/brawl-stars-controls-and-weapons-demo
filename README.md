# brawl-stars-controls-and-weapons-demo

This repository contains a compact but real gameplay system extracted from a larger Unity project.

It is designed as a **code showcase**, not a full playable game, and focuses on demonstrating clean architecture, modular gameplay systems, and practical Unity C# patterns for hiring managers and technical reviewers.

https://github.com/user-attachments/assets/04c4f91c-6d5d-4510-be4c-754fc70adf8e

---

## 🎮 What This Repo Demonstrates

### Player Input & Movement
- Mobile joystick-based movement
- Input abstraction
- Clear separation between input, movement, and animation

### Modular Weapon System
- Melee and ranged weapon handling
- Directional attack previews (line & mesh-based)
- Weapon selection via UI
- Extensible structure for adding new weapon types

### UI Interaction
- Button-driven gameplay interactions
- Weapon selection feedback
- Health bar updates linked to player state
- Event-based UI updates

### Camera & Visual Helpers
- Smooth camera follow
- Billboarding for 3D elements
- Simple emphasis / outline helpers

### Animation Integration
- Animation events bridged to gameplay code
- Animator parameter control via gameplay states
- Weapon actions connected to animation layers

---

## 🧠 Code Structure

```text
Scripts/
├── Player
├── Weapons
├── UI
├── Animation
├── Camera
├── Core
└── Misc

This mirrors the architecture used in my full project:
decoupled systems, event-based communication, and modular gameplay components.

This mirrors the architecture used in my full project:
**decoupled systems, event-based communication, and modular gameplay components.**

---

## 📝 Why This Repo Exists

This repository is part of a series of small, focused gameplay demos, each highlighting a specific system.

It allows reviewers to quickly evaluate:
- Coding style and structure
- Gameplay architecture decisions
- Practical Unity problem-solving
- Experience with mobile input, UI, weapons, math, and animations

No setup is required — the code is intended for inspection, not execution.

---

## 🛠 Technical Info

- **Unity Version:** 2022.3.x  
- **Platform:** Mobile  
- **Technologies Used:**  
  - Unity C#  
  - UGUI  
  - Event-driven architecture  
  - Gameplay math (angles, vectors, previews)  
  - Animation event bridging  
