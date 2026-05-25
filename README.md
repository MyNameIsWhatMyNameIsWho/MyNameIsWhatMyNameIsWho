<div align="center">

# Ekaterina Ch.

### Technical Designer · Gameplay Programmer

*Making game systems that feel good to play — from first prototype to production-ready.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ekaterina-chukina)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chukina.eka@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=github&logoColor=white)](https://mynameiswhatmynameiswho.github.io/personal-portfolio-site/)
[![CV](https://img.shields.io/badge/CV-Download-4B5563?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/MyNameIsWhatMyNameIsWho/MyNameIsWhatMyNameIsWho/raw/main/Ekaterina_Chukina_CV.pdf)

</div>

---

## About Me

I'm a **Technical Designer / Gameplay Programmer** based in Prague with industry experience at **Bohemia Interactive** and **Strand Forge**. I write production C# daily, think in systems, and care about code that's clean enough for the next person to build on.

- Shipped gameplay features across **4 released scenarios** at Bohemia Interactive — production C# in a professional sprint workflow  
- Designed and implemented **enemy AI state machines**, modular weapon systems, and plug-and-play interaction modules reused across multiple projects  
- Built and deployed a **VR application to Meta Quest 3** (Android platform) — extended legacy codebase, added two original mini-games, tested with real users  
- Developed a **data-driven quiz system** that cut production time from ~1 week to 2 days — localization keys, structured authoring pipeline  
- Implemented large-scale **3D simulation environments in Unreal Engine** for robotics research; performance work in C++/Blueprints  

---

## Tech Stack

**Engines**

![Unity](https://img.shields.io/badge/Unity-FFFFFF?style=flat-square&logo=unity&logoColor=black)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Godot](https://img.shields.io/badge/Godot_4-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**Craft**

![Visual Scripting](https://img.shields.io/badge/Visual_Scripting-6D28D9?style=flat-square)
![AI Behaviors](https://img.shields.io/badge/AI_Behaviors-DC2626?style=flat-square)
![Data-Driven Systems](https://img.shields.io/badge/Data--Driven_Systems-0891B2?style=flat-square)
![VR / XR](https://img.shields.io/badge/VR_%2F_XR-000000?style=flat-square&logo=meta&logoColor=white)
![Shaders](https://img.shields.io/badge/ShaderLab_%2F_HLSL-5C2D91?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Experience

| Period | Role | Company |
|--------|------|---------|
| Aug 2025 – Present | **Technical Designer / Gameplay Programmer** | Strand Forge (co-dev w/ Bohemia Interactive) |
| Sep 2024 – Sep 2025 | **Junior Technical Designer** | Bohemia Interactive |
| Feb 2023 – May 2024 | **Unreal Engine Developer / Researcher** | Multi-Robot Systems Lab, CTU FEE |

---

## Featured Projects

### [VR App for Lying Patients](https://github.com/MyNameIsWhatMyNameIsWho/VR-App-For-Lying-Patients-BP) — Bachelor Thesis
> Unity · C# · Meta Quest 2 & 3 · Android Platform

Inherited and refactored a complex Unity codebase from a prior Master's thesis, then extended it with two original VR mini-games. Built audio tutorial systems for independent use by elderly patients with no prior tech experience. Deployed to **Meta Quest (Android)** and tested hands-on with real patients at a senior care facility — requirements were discovered through observation, not documents. Iterated based on direct user and caregiver feedback until the interactions were accessible and reliable.

**Engineering highlights:** legacy code analysis and safe refactoring; XR Interaction Toolkit; mobile build pipeline for Android/Meta Quest; accessibility-first input design.

---

### [CTU Adventure](https://github.com/MyNameIsWhatMyNameIsWho/CTU_Adventure) — Java Game Engine
> Java · OOP · JSON

A tile-based game engine built in Java where levels, enemies, timers, and inventory are fully defined in **external JSON config files** — no recompile needed to change game content. Demonstrates data-driven architecture: the engine reads structured data at runtime and constructs game state from it, separating content authoring from code.

**Engineering highlights:** OOP entity system in Java; JSON-driven runtime configuration; clear separation of game logic from content data.

---

### [Snake on MZ_APO Microcontroller](https://github.com/MyNameIsWhatMyNameIsWho/Snake_MZ_APO)
> C · Hardware · Linux · Makefile

Snake built in **pure C** for the MZ_APO microcontroller board — rendered directly to an LCD display (480×320px), controlled via physical hardware knobs, with an LED strip counting down to the next apple spawn. Supports single and two-player modes with configurable difficulty.

The codebase is split into focused modules: `gameplay_utils`, `pixel_utils`, `draw_pictures`, `print_words`, `serialize_lock` — each with its own `.c/.h` pair. Built and deployed with a Makefile targeting a Linux/Debian environment over the board's network IP.

**Engineering highlights:** low-level hardware interfacing; pixel-level LCD rendering; modular C architecture; Makefile build pipeline; collision detection and game loop in C.

---

### [Tiger Escape VR](https://github.com/MyNameIsWhatMyNameIsWho/Tiger_Escape_VR_Game) — VR Course Project *(CTU VAR 2024)*
> Unity · C# · VR

A VR game built as part of the Virtual and Augmented Reality course at CTU. C# accounts for 72% of the codebase, with custom shaders rounding out the rest.

---

### [Balcony](https://github.com/MyNameIsWhatMyNameIsWho/Balcony) — Solo Narrative Game *(2026)*
> Godot 4.1 · GDScript · GDShader

A short narrative game about watching strangers through apartment windows. All story content lives in **JSON files** (`windows.json`, `endings.json`, `flat.json`, `intro.json`) loaded by a `ContentDB` singleton — no text in code. Session state (fragments, avoidance count) drives one of **3 endings** via `GameState`. Separate systems for dialogue (`dialogue_manager`), camera transitions, window hover/selection, and a custom rain shader. Built solo from concept through implementation.

---

### [Chess + Custom Figures](https://github.com/MyNameIsWhatMyNameIsWho/chess-python-oop)
> Python · OOP

Full chess implementation in Python extended with a **custom "new figures" game mode** — piece behaviour is defined by class inheritance, making new piece types addable without modifying existing move validation logic. Early but deliberate application of OOP extensibility principles.

---

## GitHub Stats

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=MyNameIsWhatMyNameIsWho&style=for-the-badge&color=6366f1&label=PROFILE+VIEWS)

[![Total Contributions](https://streak-stats.demolab.com?user=MyNameIsWhatMyNameIsWho&theme=dark&hide_border=true&date_format=j%20M%5B%20Y%5D&hide_current_streak=true&hide_longest_streak=true)](https://github.com/MyNameIsWhatMyNameIsWho)

</div>

---

## Education

- **B.Sc. Computer Science – Games and Computer Graphics** · Czech Technical University in Prague *(2022 – 2025)*  
- **Erasmus+ Exchange · Game Development** · Metropolia University of Applied Sciences, Helsinki *(Autumn 2023)* · GPA 4.0  
- **Summer Course · Psychology and Social Connections** · University of Oxford, Lady Margaret Hall *(Jun – Jul 2025)* · Grade: A

---

<div align="center">

*Prague, CZ · Open to opportunities in gameplay programming & technical design*

</div>
