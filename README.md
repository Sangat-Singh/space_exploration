# 🌌 Stellar.log

**Stellar.log** is an immersive, interactive space exploration website that brings space history, planetary systems, and futuristic 3D models to life — all in one animated, responsive, and AI-powered platform.

![screenshot](./preview.png)

---

## 🚀 Features

### 🔭 1. **On This Day: Space Events**
- Displays **real space-related events** that happened on the current date in history using the Wikipedia API.
- ✅ **Space-related filter** is enabled by default (toggle to show all historical events).
- ✅ Events include images, years, descriptions, and confidence scores.
- 🔍 Search functionality for quick exploration of specific keywords.

---

### 🪐 2. **Planet Showcase**
- Explore all major planets in our solar system through an animated 3D interface.
- ✅ View each planet with orbital motion and informative visuals.
- ✅ Click on a planet to display its **detailed description**.
- 🔊 Toggle **audio narration** to hear the description of each planet using text-to-speech.

---

### 🛰️ 3. **Space Showcase**
- View 3D models of space technology:
  - 🛰️ Satellites
  - 🚀 Shuttles
  - 🤖 Rovers
  - 🧑‍🚀 Astronauts
  - 🛰️ Space stations
- ✅ Sidebar to switch between models with descriptions.
- ✅ Animated nebula parallax background.
- ✅ Fully interactive OrbitControls camera.

---

### 💬 4. **TaraBot: Your Space Assistant**
- A chatbot assistant docked in the bottom-right corner.
- Ask space-related questions and get responses powered by Botpress or AI.
- Toggle visibility with a click.

---

### 🧭 5. **Orbit Visualization (Bonus Mode)**
- A complete 3D **solar system orbit** mode with animated motion and camera controls.

---

### 🧩 6. **Footer**
- Includes links, credits, and copyright.
- Clean and responsive.

---

## 🧰 Technologies & Tools Used

| Category           | Stack / Tools Used                              |
|--------------------|-------------------------------------------------|
| **Frontend**        | React, JSX, CSS, Tailwind (optional)           |
| **3D Rendering**    | Three.js, @react-three/fiber, @react-three/drei |
| **API Integration** | Wikipedia REST API, SpaceDevs Launch API       |
| **Animations**      | Framer Motion, CSS Transitions, Parallax FX    |
| **Audio**           | Web Speech API (Text-to-Speech)                |
| **Chatbot**         | Botpress or ChatGPT API                        |
| **Loader**          | Custom boot loader animation with CSS Spinner  |

---

## 🧪 How to Run Locally

```bash
# Clone this repository
git clone https://github.com/your-username/stellar-log.git
cd stellar-log

# Install dependencies
npm install

# Start the server
npm start
