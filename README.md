# 🧩 Unreal Engine Blueprint Showcase

A collection of all my **Unreal Engine 5.5.4** mini-projects — built from scratch, one system at a time.
Each project focuses on a specific gameplay or visual mechanic, designed to teach, inspire, and evolve into larger systems later on.

---

## 🎞️ Project Gallery

![Project Showcase](Media/AllProjects.gif)

Explore the full breakdowns below 👇
Each project includes its **Blueprint setup**, **preview GIF**, and a short **feature list** for quick reference.

# 🎥 Project 1 – Camera Shake 
**[Read on Medium](https://medium.com/@fulton_shaun/how-to-add-camera-shake-in-unreal-engine-5-fef9d92e84ec)** | **[Watch on YouTube](https://www.youtube.com/watch?v=iNgOoYmHcuQ)**

This project demonstrates how to add a dynamic camera-shake effect using **Blueprints** in **Unreal Engine 5.5.4**.
It’s a lightweight example showing how to make explosions, impacts, or landings feel more cinematic and reactive.

---

## 🖼️ Preview

![Camera Shake Preview](Media/CameraShake.gif)

---

## 🧱 Features

- Custom **LegacyCameraShake** Blueprint (`BP_CameraShake`)
- Adjustable amplitude and frequency for pitch, yaw, roll, and location
- Triggered via keyboard input using the **Play World Camera Shake** node

# 🌞 Project 2 – Dynamic Sun & Sky 
**[Medium Guide](https://medium.com/@fulton_shaun/one-plugin-to-handle-realistic-sun-movement-in-unreal-engine-5-bb47f34da4c0)** • **[YouTube Tutorial](https://www.youtube.com/watch?v=ubcIAoH_3D8)**


This project demonstrates how to create natural, evolving sunlight using _Unreal Engine 5.5.4’s_ **Day Sequence** plugin.
It’s a lightweight setup that makes your world feel alive with automatic sun and sky movement — completely Blueprint-free.

---

## 🖼️ Preview

![Dynamic Sun and Sky Preview](Media/DynamicSunSky.gif)

---

## 🧱 Features

- Uses the **Day Sequence (Experimental)** plugin for real-time sun and sky animation
- Automatically manages **Directional Light**, **Sky Atmosphere**, and **Skylight**
- Simple, Blueprint-free setup ideal for quick lighting prototypes
- Fully adjustable through the **Details** panel for artistic control

# 🎥 Project 3 – Stealth & Dash AI 
**[Medium Guide]([https://medium.com/yourlink](https://medium.com/@fulton_shaun/stealth-meets-speed-building-a-spot-and-dash-system-in-unreal-engine-5-bcd0cfc9b43c))** • **[YouTube Tutorial]([https://youtu.be/yourlink](https://www.youtube.com/watch?v=YTrbINYqTAc&embeds_widget_referrer=https%3A%2F%2Fmedium.com%2F%40fulton_shaun%2Fstealth-meets-speed-building-a-spot-and-dash-system-in-unreal-engine-5-bcd0cfc9b43c&embeds_referring_euri=https%3A%2F%2Fcdn.embedly.com%2F&embeds_referring_origin=https%3A%2F%2Fcdn.embedly.com&source_ve_path=MjM4NTE))**

This project shows how to create a simple stealth system in **Unreal Engine 5.5.4**, featuring a stationary guard that can detect the player using **Pawn Sensing** and a manual dash mechanic for quick escapes.

---

## 🖼️ Preview

![Stealth and Dash AI Preview](Media/StealthDashAI.gif)

---

## 🧱 Features

- Player **dash mechanic** using LaunchCharacter and directional velocity
- AI guard with **Pawn Sensing** for player detection
- Smooth rotation toward player using **Find Relative Look At Rotation**
- Configurable **vision range** and detection angle
- Designed for stealth or action prototypes

---

## ❤️ Project 4 – Health & Death System

This project demonstrates how to build a simple yet complete **Health and Death System** in **Unreal Engine 5.5.4**, combining UI, player damage logic, and full ragdoll physics.
It’s an essential gameplay foundation that makes any project feel more alive and reactive.

---

### 🖼️ Preview

![Health and Death System Preview](Media/HealthSystem.gif)

---

### 🧱 Features

- **Player Health System** using the `Event Any Damage` node
- **Dynamic Damage Handling** with subtraction and health tracking
- **Death Logic** featuring ragdoll physics and input disable
- **UI Health Bar** bound to player health through a progress bar
- **Automatic On-Screen Display** at game start via `Create Widget` and `Add to Viewport`
- Fully modular — can be extended into **combat**, **survival**, or **RPG** systems

---

## 🎥 Project 5 – Third-Person to First-Person Camera Toggle

This project demonstrates how to **switch between third-person and first-person views** in **Unreal Engine 5.5.4** using Blueprints.
It’s a lightweight, game-ready setup inspired by titles like _Skyrim_ and _GTA_, allowing players to toggle perspectives instantly with a single key.

---

### 🖼️ Preview

![Camera Toggle Preview](Media/CameraToggle.gif)

---

### 🧱 Features

- **First-Person Camera** attached to the character’s head socket for accurate viewpoint
- **Toggle System** using `FlipFlop` and `Branch` nodes on the **V** key
- **Automatic Activation/Deactivation** of first-person and follow cameras
- **Camera Boom Reset** for seamless third-person return
- Fully modular — extendable for **cinematic transitions**, **FOV blending**, or **hybrid combat systems**

---

## 🌧️ Project 6 – Niagara Rain System

This project demonstrates how to create a **realistic rain effect** in **Unreal Engine 5.5.4** using Niagara.
It’s a simple yet cinematic weather system that adds atmosphere and realism to any environment — perfect for moody, story-driven, or open-world scenes.

---

### 🖼️ Preview

![Niagara Rain System Preview](Media/NiagaraRain.gif)

---

### 🧱 Features

- **Fog-based atmosphere** setup using Exponential Height Fog (density 2.0)
- **Niagara System (NS_Rain)** created from the Fountain emitter template
- **GPU-accelerated simulation** for large-scale performance
- **High-density rainfall** with 3000 spawn rate and 4000x4000 area coverage
- **Realistic downward velocity** and motion-aligned sprites for natural streaks
- **Custom sprite scaling** (3x50) for elongated raindrop visuals
- **Bounds scaling and placement** optimized to prevent culling during gameplay
- Fully modular — can be expanded with **wind**, **splashes**, or **thunder effects**
