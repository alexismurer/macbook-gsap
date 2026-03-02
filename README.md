# 💻 MacBook GSAP Experience

An Apple-inspired MacBook product website built to experiment with **GSAP animations**, **Three.js 3D rendering**, and smooth product-style storytelling.

This project recreates the premium interactive feel of modern Apple landing pages — combining scroll-based animations, 3D models, lighting setups, and responsive layouts.

---

## ✨ Overview

This project focuses on:

- 🎞 GSAP timeline orchestration
- 🧊 Real-time 3D rendering with Three.js
- 🎥 Camera & model transitions
- 💡 Studio-style lighting setup
- 📱 Responsive behavior across devices

---

## 🚀 Tech Stack

### Core

- ⚛️ React 19
- ⚡ Vite
- 🎨 TailwindCSS v4

### Animation

- 🎞 GSAP
- @gsap/react

### 3D

- 🧊 Three.js
- @react-three/fiber
- @react-three/drei

### State & Utilities

- 🗂 Zustand
- 📱 react-responsive
- 🧩 clsx

---

## 📂 Project Structure

```bash
src/
│
├── components/
│   ├── models/
│   │   ├── Macbook-14.jsx
│   │   ├── Macbook-16.jsx
│   │   └── Macbook.jsx
│   │
│   ├── three/
│   │   ├── ModelSwitcher.jsx
│   │   └── StudioLights.jsx
│   │
│   ├── Features.jsx
│   ├── Footer.jsx
│   ├── Hero.jsx
│   ├── Highlights.jsx
│   ├── NavBar.jsx
│   ├── Performance.jsx
│   ├── ProductViewer.jsx
│   └── Showcase.jsx
│
├── constants/
│   └── index.js
│
├── store/
│   └── index.js
│
├── App.jsx
├── main.jsx
└── index.css
```

---

## 🧠 Architecture Highlights

### 🎥 ProductViewer

Handles the 3D canvas rendering and connects:

- Model selection
- Camera transitions
- GSAP-driven animations

### 🧊 models/

Contains separate MacBook 14" and 16" 3D model components.

### 💡 StudioLights

Creates a clean, Apple-like lighting setup for a premium product feel.

### 🔄 ModelSwitcher

Controls switching between models with smooth transitions.

### 🗂 Zustand Store

Centralized state management for selected model's color, scale and textures

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/alexismurer/macbook-gsap.git
cd macbook-gsap
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

---

## 🏗 Production Build

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 🎬 Animation Approach

This project uses:

- GSAP timelines for section-based animations
- Scroll-triggered transitions
- Coordinated DOM + WebGL animations
- Smooth camera and model rotations
- Performance-aware animation batching

---

## 🎯 Key Learnings

- Integrating GSAP cleanly inside React components
- Synchronizing UI and Three.js animations
- Managing animation state properly
- Optimizing 3D performance in a React app

---

## 📄 License

This project was built for learning and portfolio purposes.
