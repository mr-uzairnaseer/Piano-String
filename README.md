# StringMaster - React Application

> **Note**: This project has been migrated from a static HTML website to a modern React application using Vite.

![StringMaster Screenshot](Screenshot.png)

## 🎵 Overview

StringMaster is a browser-based music production suite designed for artists to learn, sketch, and record ideas anywhere. It features a suite of virtual instruments including a guitar, piano, bass, and drum machine, all powered by the Web Audio API.

## 🚀 Features

- **Interactive Strings**: Virtual guitar with chord presets and strumming.
- **Grand Piano Engine**: Low-latency piano synthesis.
- **Analog Bass**: Monosynth for deep basslines.
- **Rhythm Engine**: 16-pad MPC-style beat pad.
- **Atmosphere**: Drone generator for ambient textures.
- **Lead Synth**: High-pitch glide synth for solos.
- **Responsive Design**: Works on desktop and mobile.

## 🛠️ Tech Stack

- **Framework**: React 18 + Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Audio**: Web Audio API (Native)

## 📦 Installation & Running

1.  **Install Dependencies**:
    ```bash
    npm install
    ```

2.  **Start Development Server**:
    ```bash
    npm run dev
    ```
    The app will run at `http://localhost:5173`.

3.  **Build for Production**:
    ```bash
    npm run build
    ```

## 📂 Project Structure

```
src/
├── components/
│   ├── layout/       # Header, Footer
│   ├── sections/     # Hero, Features, Pricing, etc.
│   ├── tools/        # Instrument components (Guitar, Piano, etc.)
│   └── legal/        # Privacy Policy, Terms of Service
├── hooks/            # Custom React Hooks (useAudioEngine)
└── App.jsx           # Main Application Layout
```

## 📝 License

© 2026 StringMaster. All rights reserved.
