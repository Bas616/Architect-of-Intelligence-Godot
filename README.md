# The Architect of Intelligence [Godot Engine Cinematic]

[![Status](https://img.shields.io/static/v1?label=status&message=completed&color=55ff88&style=for-the-badge)](https://github.com/Bas616/Architect-of-Intelligence-Godot)
[![Engine](https://img.shields.io/badge/Rendered_In-Godot_4.2-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white)](https://godotengine.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

This repository contains the complete Godot Engine 4 project for **"The Architect of Intelligence"**, a conceptual cinematic short film rendered entirely in-engine. This project eschews traditional video editing software in favor of leveraging Godot's powerful animation, shader, and sequencing tools to create a finished cinematic product directly from the source code.

The film serves as a visual metaphor for the role of an AI Systems Architect, exploring the journey from chaotic data to a synthesized consciousness. It was created for an academic project for a "Modern Innovations and Technology" course.

**[▶️ Watch the Final Render on YouTube](https://youtu.be/TBx6ZQZo940?si=fVoJ1syDO3Yxy8Sg)** 

---

## I. Philosophy: Code as Camera

The core philosophy of this project was to treat the game engine not merely as a platform for games, but as a virtual film studio. By controlling every visual element—camera movement, UI animations, shaders, and environmental effects—through Godot's master `AnimationPlayer`, we achieve a level of precision and programmatic control that is impossible with standard video editing tools.

This approach demonstrates:
-   **Technical Proficiency:** Mastery of Godot's animation system, spatial shaders (GLSL), and scene management.
-   **Efficiency:** The ability to iterate and re-render entire sequences simply by adjusting keyframes and code.
-   **Creative Control:** The fusion of developer, animator, and cinematographer roles into a single, cohesive workflow.

## II. Technical Features

-   **In-Engine Rendering:** The final video was exported as an `.avi` sequence directly from Godot using the built-in "Movie Maker" functionality, bypassing the need for screen recording.
-   **Single-Scene Cinematic:** The entire ~70-second sequence is controlled by a single `AnimationPlayer` within the main scene (`master_cinematic.tscn`).
-   **Procedural Environment:** The "Matrix Ocean" and other background effects are driven by custom shaders.
-   **Synchronized Audio/Visuals:** All narration and sound effects are triggered by the `AnimationPlayer`'s "Call Method Track" to ensure perfect synchronization with the animated visuals.

## III. How to Use & Explore

1.  Clone this repository.
2.  Open the project using **Godot Engine version 4.5** or newer.
3.  The main scene is located at `main.tscn`.
4.  Press `F5` to play the cinematic in real-time within the editor.

## IV. Credits & License

-   **Concept & Development:** [Bas616](https://github.com/Bas616)
-   **Sound Effects:** All sound effects are from [Taira Komori's Free Sound Effects](https://taira-komori.jpn.org/) and are used under their terms of service.
-   **Narration Synthesis:** Google Gemini 2.5 Pro TTS.

This project is licensed under the MIT License. See the `LICENSE` file for details.
