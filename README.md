# 🌌 The Breathing Universe Portal

Interactive visualization of the fundamental architecture of reality based on **Arnon Daniel Katz's (Noni)** Breathing Universe Theorem.

## 📜 Overview
This project is a scientific visualization portal designed to explore the geometric and temporal dynamics of a toroidal universe. It translates complex mathematical theorems into an interactive 3D environment, allowing users to manipulate space-time parameters and observe the resulting quantum behaviors.

## 📐 Geometric Mapping & Concept Relationships

Using the **Neo-Euclid** framework, the portal maps HUD (2D) interactions to Toroidal (3D) coordinates.

### The conceptual framework:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#f5f3ef', 'primaryTextColor': '#2a2520', 'primaryBorderColor': '#1a7a9e', 'lineColor': '#a83068', 'secondaryColor': '#b8860b', 'tertiaryColor': '#f5f3ef'}}}%%
graph TD
    subgraph "HUD Control (Dials)"
        T[θ Cyan Dial] ---|Revolution Velocity| R(Macro Orbit)
        P[φ Magenta Dial] ---|Sectional Velocity| S(Micro Spin)
    end

    subgraph "Mathematical Projection"
        R -->|Mapping| Pm[Point of Motion P_m]
        S -->|Mapping| Pphi[Torus Point P_φ]
    end

    subgraph "Emergent Spacetime"
        Pm & Pphi -->|Frequencies| B{The Breathing Effect}
        W[Temporal Warp x] -.->|Scaling| B
    end

    style T fill:#1a7a9e,color:#fff
    style P fill:#a83068,color:#fff
    style Pm fill:#fff,stroke:#2a2520,color:#2a2520
    style Pphi fill:#a83068,stroke:#2a2520,color:#fff
    style B fill:#b8860b,color:#fff
    style W fill:#fff,stroke:#b8860b,color:#b8860b
```

---

### 1. The $\theta$ Dimension (Major Axis)
*Represented by the outer cyan circle.*
- **Coordinate:** $Orbit_{\theta}$
- **Motion:** Orbital path around the central singularity of the torus.
- **Physics:** Represents the macro-scale revolution of energy ($P_m$).

### 2. The $\phi$ Dimension (Minor Axis)
*Represented by the inner magenta circle.*
- **Coordinate:** $Section_{\phi}$
- **Motion:** Centrifugal spin within the torus tube cross-section.
- **Physics:** Represents the micro-scale phase/wave state ($P_\phi$).

---

## 🔬 Toroidal Mathematics

The graphical projection follows the parametric equations for a Torus:

$$
\begin{cases} 
x = (R + r \cos \phi) \cos \theta \\
y = (R + r \cos \phi) \sin \theta \\
z = r \sin \phi 
\end{cases}
$$

Where:
- $R$: Major Radius (distance from center to tube center).
- $r$: Minor Radius (thickness of the tube).
- $\theta \in [0, 2\pi]$ (controlled by the Cyan HUD Dial).
- $\phi \in [0, 2\pi]$ (controlled by the Magenta HUD Dial).

## ✨ Features
- **Neo-Euclid Theme:** A scientific aesthetic inspired by historical mathematical treatises.
- **Dual Mode:** Choose between **Manuscript Mode** (Light) and **Cosmic Mode** (Dark).
- **Interactive HUD:** Precise 270° dial controls with dynamic stroke and scaling.
- **Temporal Drive:** Play/Pause controls with variable time-warping ($Warp_x$).

## 🛠 Technical Stack
- **Three.js:** Primary 3D engine.
- **Mermaid.js:** Concept diagramming.
- **LaTeX:** Mathematical notation.

---
*Created by Jamagax in collaboration with AI, dedicated to the exploration of the Breathing Universe.*
