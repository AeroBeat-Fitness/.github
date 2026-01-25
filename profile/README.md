# Welcome to AeroBeat Workouts

**AeroBeat** is an open-source, modular rhythm game platform designed to democratize fitness gaming. Think of it as the "YouTube of Workout Games"—a place where hardware inputs, gameplay mechanics, and community content can be mixed and matched freely.

## 🚀 The Vision

We are building a platform, not just a game. Our architecture separates **Input** (How you move), **Logic** (The rules of the game), and **Content** (The music and visuals).

*   **Hardware Agnostic:** Play using a Webcam (MediaPipe), VR Controllers, JoyCons, or even a Keyboard.
*   **Modular Gameplay:** Swap the "Core Mechanic" instantly. Go from **Boxing** (punching targets) to **Flow** (Beat Saber style movement) without changing the engine.
*   **Community First:** Built for modding. Artists can skin targets, Musicians can map songs, and Coders can write new input drivers.

## 📚 Documentation

*   **[Official Documentation Site](https://aerobeat-workouts.github.io/aerobeat-docs/)**
*   **[Game Design Document](https://aerobeat-workouts.github.io/aerobeat-docs/gdd/concept/)**
*   **[Technical Architecture](https://aerobeat-workouts.github.io/aerobeat-docs/architecture/overview/)**

## 📂 Repository Ecosystem

| Tier | Repository | Role | License |
| :--- | :--- | :--- | :--- |
| **Assembly** | **`aerobeat-assembly-*`** | **The Product.** Specific editions (Community, Arcade). | **GPLv3** |
| **Core** | **`aerobeat-core`** | **The Hub.** Interfaces, Data Types, Global Constants. | **MPL 2.0** |
| **UI Core** | **`aerobeat-ui-core`** | **UI Logic.** Base classes (ViewModel) for components. | **MPL 2.0** |
| **Tool** | **`aerobeat-tool-*`** | **Services.** Singleton Managers (ex: APIs, Analytics). | **MPL 2.0** |
| **Input** | **`aerobeat-input-*`** | **Hardware Drivers.** (Camera, VR, Watch). | **MPL 2.0** |
| **UI Kit** | **`aerobeat-ui-kit-*`** | **Visual Library.** Themed scenes inheriting UI Core logic. | **MPL 2.0** |
| **UI Shell** | **`aerobeat-ui-shell-*`** | **Interaction Layer.** Platform-specific screens. | **GPLv3** |
| **Feature** | **`aerobeat-feature-*`** | **Gameplay Logic.** Mechanics & Base Scenes (Boxing, Flow). | **GPLv3** |
| **Skins** | **`aerobeat-skins-*`** | **Gameplay Visuals.** Gloves, Targets, Obstacles. | **CC BY-NC 4.0** |
| **Avatars** | **`aerobeat-avatars-*`** | **Characters.** Player/Coach models. | **CC BY-NC 4.0** |
| **Cosmetics** | **`aerobeat-cosmetics-*`** | **Accessories.** Hats, Glasses. | **CC BY-NC 4.0** |
| **Environments** | **`aerobeat-environments-*`** | **Levels.** Lighting, Skyboxes. | **CC BY-NC 4.0** |
| **Asset** | **`aerobeat-asset-*`** | **System Assets.** UI Icons, Mock Data. | **CC BY-NC 4.0** |
| **Docs** | **`aerobeat-docs`** | **Manual.** Documentation Website. | **CC BY-NC 4.0** |
| **Vendor** | **`aerobeat-vendor`** | **3rd Party Tools.** Utilities and Helpers. | *(As Upstream)* |

## 🤝 Contributing

We welcome contributions! Please read our **Contributing Guide** and **Code of Conduct** before getting started.

> **Note:** All code contributions require signing our **CLA**.
