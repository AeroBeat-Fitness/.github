# Welcome to AeroBeat Fitness

**AeroBeat** is an open-source, modular rhythm game platform designed to democratize fitness gaming. Think of it as the "YouTube of Workout Games"—a place where hardware inputs, gameplay mechanics, and community content can be mixed and matched freely.

## 🚀 The Vision

We are building a platform, not just a game. Our architecture separates **Input** (How you move), **Logic** (The rules of the game), and **Content** (The music and visuals).

*   **Hardware Agnostic:** Play using a Webcam (MediaPipe), VR Controllers, JoyCons, or even a Keyboard.
*   **Modular Gameplay:** Swap the "Core Mechanic" instantly. Go from **Boxing** (punching targets) to **Flow** (Beat Saber style movement) without changing the engine.
*   **Community First:** Built for modding. Artists can skin targets, Musicians can map songs, and Coders can write new input drivers.

## 📚 Documentation

*   **[Official Documentation Site](https://aerobeat-fitness.github.io/aerobeat-docs/)**
*   **[Game Design Document](https://aerobeat-fitness.github.io/aerobeat-docs/gdd/concept/)**
*   **[Technical Architecture](https://aerobeat-fitness.github.io/aerobeat-docs/architecture/overview/)**

## 📂 Repository Ecosystem

| Repository | Role | License |
| :--- | :--- | :--- |
| **[`aerobeat-assembly-community`](https://github.com/AeroBeat-Fitness/aerobeat-assembly-community)** | The Game Client (Community Edition). | **GPLv3** |
| **`aerobeat-core`** | The Engine Hub. Contracts, Signals, and Data Types. | **MPL 2.0** |
| **`aerobeat-input-*`** | Hardware Drivers (Webcam, VR). | **MPL 2.0** |
| **`aerobeat-ui-core`** | UI Logic Layer (ViewModel). | **MPL 2.0** |
| **`aerobeat-ui-kit-*`** | Visual Component Libraries. | **MPL 2.0** |
| **`aerobeat-ui-shell-*`** | Interaction Shells (Mobile vs VR). | **GPLv3** |
| **`aerobeat-feature-*`** | Gameplay Logic (e.g., Boxing, Flow). | **GPLv3** |
| **`aerobeat-asset-*`** | Content Packs (Skins, Environments). | **CC BY-NC 4.0** |

## 🤝 Contributing

We welcome contributions! Please read our **Contributing Guide** and **Code of Conduct** before getting started.

> **Note:** All code contributions require signing our **CLA**.