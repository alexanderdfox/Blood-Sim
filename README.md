# Quantum Multiscale Fusion Engine

An interactive, high-fidelity physics simulation that bridges the gap between **Subatomic Quantum Mechanics**, **Biological Plasma (Blood)**, and **Celestial Mechanics (Space)**. Build elements from the ground up, observe their chemistry, and manipulate the fundamental constants of the universe.

---

## 🔬 Core Simulations

The engine allows you to toggle between three distinct physical scales, each governed by unique mathematical models:

### 🌌 Deep Space (Macro Scale)

* **Physics:** Newtonian Gravity (`F = G * m1 * m2 / r^2`)
* **Behavior:** Zero-friction environment. High-mass atoms (like Iron) act as gravitational anchors.
* **Goal:** Create stable orbital systems or trigger gravitational collapses.

### 🩸 Plasma / Blood (Meso Scale)

* **Physics:** Stokes' Viscous Drag and Molecular Cohesion
* **Behavior:** Atoms move through a thick medium with a rhythmic "heartbeat" pulse.
* **Goal:** Observe how hemoglobin-like structures and oxygen molecules interact in a fluid environment.

### ⚛️ Quantum (Micro Scale)

* **Physics:** Strong Force Approximation and Probability Clouds
* **Behavior:** Atoms exhibit high-frequency vibration and "uncertainty" glows.
* **Goal:** Trigger nuclear fusion via the Strong Force to synthesize heavy elements.

---

## 🛠 Features

* **Dynamic Fusion Engine:** High-speed collisions merge atoms. Atomic numbers (Z) sum together to create entirely new elements.
* **IUPAC Naming System:**

  * Standard Elements: Recognizes H, He, C, O, Fe, etc.
  * Synthetic Isotopes: Automatically generates IUPAC names (e.g., Ununpentium) for synthesized elements beyond the standard periodic table.
* **Tactile Discovery:** Click or tap any moving atom to inspect its chemical properties, atomic mass, and real-world description.
* **Bohr Model Visualization:** Electron shells are rendered based on the `2n^2` rule, with orbital speeds relative to their energy levels.
* **Temporal Controls:**

  * **Play/Pause:** Freeze the universe to inspect complex clusters.
  * **Time Dilation:** Scale the flow of time from a frozen state to 5× speed.
  * **Gravity Well:** Toggle a global central force to simulate stellar formation.

---

## 🎮 How to Use

1. **Spawn Atoms:** Click and drag on the canvas. The length and direction of your drag determine the atom's initial velocity.
2. **Select Element:** Use the UI buttons to choose your starting "seed" (H, C, Fe).
3. **Fuse:** Launch a light atom (Hydrogen) at a heavy atom (Carbon) at high speed. If the "Heat" (relative velocity) is high enough, they will fuse into Nitrogen (Z=7).
4. **Inspect:** Click on any moving atom to open the Discovery Card and see what you have created.
5. **Shift Scales:** Use the top toggle to instantly change the laws of physics governing your particles.

---

## 📝 Mathematical Constants

* **Standard Gravity (G):** Adjustable via the UI slider.
* **Fusion Threshold:** Requires a relative velocity `Δv > 2.5` (scaled by mode).
* **Atomic Radius:** Calculated as `r = 4 + Z * 3`
* **Electron Capacity:** Shell `n` holds `2n^2` electrons

> **Note:** This simulation is an artistic and educational representation of physics. While it uses real-world formulas, some constants are "softened" (e.g., adding a distance epsilon) to prevent infinite forces and ensure a smooth web-based experience.
