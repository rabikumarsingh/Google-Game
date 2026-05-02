<div align="center">
<img width="1200" height="475" alt="Voxel Countdown Banner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />

# Voxel Countdown

**Explore floating voxel worlds, conquer gravity, and race against the clock!**

[![AI Studio](https://img.shields.io/badge/Built%20with-AI%20Studio-blue)](https://ai.studio/apps/7045493a-bbd3-4344-afb0-d48d66ef3c91)
[![React](https://img.shields.io/badge/Powered%20by-React-61DAFB)](https://reactjs.org/)
[![Three.js](https://img.shields.io/badge/Graphics-Three.js-black)](https://threejs.org/)

</div>

---

## 🕹️ The Game

**Voxel Countdown** is a mind-bending 3D platformer where you traverse floating stages shaped like massive voxel numbers. From Stage 30 down to Stage 1, each level presents a unique challenge in a thrilling race against survival.

### Key Features
- **30 Unique Stages**: Progress through 30 distinct voxel number worlds.
- **Hidden Key Mechanics**: Every stage requires finding a hidden key to unlock the path to the next number.
- **Collectibles**: Grab coins to boost your score and maximize your ranking.
- **Dynamic Gravity**: Experience unique 3D movement where the camera and player adapt to the voxel terrain.
- **Atmospheric Experience**: High-energy synthwave music and vibrant "Cyber-Retro" visuals.

---

## 🎮 Controls

| Action | Control (Desktop) | Control (Mobile) |
| :--- | :--- | :--- |
| **Move** | `W`, `A`, `S`, `D` or Arrows | Virtual Joystick (Left) |
| **Camera Rotate**| `J`, `L` / `I`, `K` | Virtual Joystick (Right/Swipe) |
| **Zoom** | `Q`, `E` | UI Buttons |
| **Reset Camera** | `R` | UI Button |
| **Mute Music** | `M` | - |

---

## 🛠️ Technical Stack

This application is built with modern web technologies:

- **Frontend**: [React](https://reactjs.org/) for UI and Game state management.
- **3D Engine**: [React Three Fiber](https://github.com/pmndrs/react-three-fiber) for declarative 3D scenes.
- **Physics**: [Rapier](https://rapier.rs/) via `@react-three/rapier` for fast voxel collisions.
- **Graphics Components**: [Drei](https://github.com/pmndrs/drei) for advanced 3D helpers.
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for a sleek, responsive HUD.
- **Animations**: [Motion](https://www.framer.com/motion/) for cinematic transitions and UI effects.
- **Post-Processing**: Screen effects for that "Retro-Future" glow.

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- `npm`

### Installation

1. **Clone or Download** the source code.
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Environment Setup**:
   Create a `.env.local` file and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. **Launch Application**:
   ```bash
   npm run dev
   ```

---

## 🌟 Credits

Developed with the power of **Google AI Studio Build**.

[View in AI Studio](https://ai.studio/apps/7045493a-bbd3-4344-afb0-d48d66ef3c91)
