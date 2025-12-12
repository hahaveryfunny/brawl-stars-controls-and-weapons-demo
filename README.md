# brawl-stars-controls-and-weapons-demo
Brawl-Stars Style Controls & Modular Weapon System (Unity C# Showcase)

https://github.com/user-attachments/assets/04c4f91c-6d5d-4510-be4c-754fc70adf8e

This repository contains a compact but real gameplay system extracted from my larger Unity project.
It demonstrates:

Mobile joystick controls

A modular weapon system (melee, ranged, directional previews)

UI interactions for weapon selection

Basic animation hooks

Player movement logic

Core gameplay utilities (health, camera follow, billboarding, etc.)

The goal of this repo is not to provide a full runnable game, but to showcase the clarity, structure, and modularity of my Unity C# code for hiring managers and technical reviewers.

⭐ What This Repo Demonstrates
🎮 1. Player Input & Movement

Scripts like PlayerMovement, FloatingJoystick, JoystickFunction provide:

Mobile-style movement controls

Input abstraction

Smooth directional control

Clear separation between input → movement → animation

🔫 2. Modular Weapon System

This mini-repo includes several weapon-related scripts:

WeaponButton

WeaponWheelController

GripPoint

WeaponManager

MeleeArcVisualizer

LinePreview

PreviewMesh

These show:

How weapons are selected and activated

How melee arcs and ranged previews are calculated

How weapon UI communicates with gameplay code

How extension points are created for new weapon types

Weapon previews are generated using both line and mesh-based approaches, demonstrating practical gameplay math and visualization logic.

🎨 3. UI Interaction and Feedback

Scripts such as:

InventoryButton

WeaponButton

SelectedWeaponImage

SelectedWeaponText

ButtonSFX

HealthBarUI

These show:

Button-driven interactions

Updating UI elements based on gameplay events

Displaying selected weapons

UI-based player feedback

Health bar updates linked to player health

🎥 4. Camera & Visual Helpers

Includes:

CameraManager

FollowCamera

Billboard

Outline

These demonstrate:

Smooth camera follow

3D objects always facing the camera (billboarding)

Simple outline/emphasis system

🩹 5. Animation Bridges

Scripts like:

AnimationManager

AnimationEventBridge

Show how I connect:

Animation events → code

Gameplay states → animator parameters

Runtime weapon controls → animation layers

❤️ 6. Core Gameplay Systems

Health

Settings

Utility scripts

These provide foundational logic used by gameplay and UI.

🧠 Code Structure

Scripts are categorized into logical folders:

Scripts/
│
├── Player
├── Weapons
├── UI
├── Animation
├── Camera
├── Core
└── Misc


This reflects the architecture used in my complete project:
decoupled systems communicating through events, clean responsibilities, and modular gameplay components.

📸 Preview

Place your GIF here:

Documentation/preview.gif


For example:

Joystick movement

Weapon wheel selection

Melee arc preview

Ranged line preview

A 3–6 second silent GIF is enough.

📝 Why This Repo Exists

This repository is part of a series of showcase mini-repos, each focused on a specific gameplay system.
It helps hiring managers quickly inspect:

My coding style

My architecture decisions

My ability to build modular gameplay systems

My experience with Unity UI, input, weapons, math, and animations

No setup is required to explore the code.

🛠️ Technologies Used

Unity C#

UI Toolkit / UGUI

ScriptableObjects (in main project)

Mobile control design

Gameplay math (angles, previews, direction vectors)

Animation event bridging
