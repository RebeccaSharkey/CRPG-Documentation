---
title: Code Documentation Hub
---
# Code Documentation Hub

Welcome to the **Code Documentation Hub** for the project. This page serves as the central resource for all technical details, including system architecture, core classes, engine integration, and gameplay mechanics. Whether you're a developer, contributor, or interested party, this hub will provide you with a detailed understanding of the game's code and systems.

---

## Sections

### 1. System Architecture
This section provides a comprehensive overview of the core **C++ architecture** that drives the game. It includes class hierarchies, key systems, and how different components communicate.

- **Main Classes**: Breakdowns of the main game classes such as `TacticalPlayerController`, `TacticalCharacter`, and the various manager classes.
- **Subsystems**: An overview of core subsystems like the **Gameplay Ability System (GAS)**, **Combat System**, and **Character Stats Management**.
- **Data Structures**: Detailed descriptions of the primary data structures used for character stats, ability calculations, and inventory systems.

---

### 2. Gameplay Ability System (GAS)
The **Gameplay Ability System** (GAS) is a key feature in Unreal Engine 5 that handles abilities, attributes, and effects. This section dives deep into:

- **Ability System Component**: How the ability system is implemented for each character and how abilities are triggered.
- **Attributes and Modifiers**: How the player’s stats (e.g., health, mana, stamina) are set up and modified by abilities.
- **Gameplay Effects**: A guide to creating custom effects (e.g., damage, healing, buffs, debuffs) and applying them to players and enemies.
- **Ability Activation**: How abilities are activated, and the process flow for determining their success, cost, and cooldown.

---

### 3. Movement and Camera Systems
This section outlines how **player movement** and **camera systems** are implemented in the game, covering both in-combat and out-of-combat scenarios.

- **Character Movement**: Detailed explanation of how characters are moved across the map using navigation systems and pathfinding.
- **Camera Control**: How the player can pan, zoom, and rotate the camera to view the battlefield. Includes information on both **WASD controls** and **mouse panning**.
- **Party Management**: Managing multiple characters in a tactical party system, including switching between different characters.

---

### 4. Combat System and Turn-Based Logic
The **Combat System** is one of the most important aspects of the game. This section provides an overview of the **turn-based system**, initiative, and action management.

- **Turn-Based Combat Flow**: Explanation of the game's turn-based logic, including how turns are calculated and how actions (movement, attacks, abilities) are resolved.
- **Action Points (AP) System**: A breakdown of how **AP** is consumed for movement, attacks, and special abilities. This also includes how AP is regenerated and how it interacts with player stats.
- **Initiative System**: How the initiative order is calculated and how players can influence turn order with their characters' stats.

---

### 5. Code Snippets and Samples
This section provides practical **code snippets** that demonstrate key functionalities, including player actions, camera movement, and more.

- **Character Movement**: Example code for character movement using Unreal Engine’s **Navigation System**.
- **Ability Activation**: A sample function that shows how abilities are triggered and how their effects are applied.
- **Custom Gameplay Effects**: How to create and apply custom gameplay effects to players or enemies.

---

### 6. Optimization and Best Practices
To ensure smooth performance, this section outlines the **optimization strategies** used in the project, focusing on efficient memory usage and gameplay logic optimization.

- **Blueprint and C++ Integration**: Tips for balancing blueprints with C++ for optimal performance and rapid prototyping.
- **Memory Management**: Efficient handling of large game worlds, assets, and data using Unreal Engine's **World Partition** system.
- **Performance Profiling**: Tools and methods for profiling the game’s performance to identify bottlenecks and improve frame rates.

---

### 7. Unreal Engine Workflows
This section describes the custom tools, pipelines, and workflows that were created in **Unreal Engine 5** to streamline development and improve collaboration.

- **Custom Tools**: Editor extensions, automated testing tools, and asset management pipelines built for efficiency.
- **Editor Workflows**: How we handle level streaming, asset loading, and in-editor debugging to speed up the development process.
- **Multiplayer and Networked Systems**: How networked systems are being implemented for potential future multiplayer features.

---

## Conclusion
This **Code Documentation Hub** serves as the central resource for all technical aspects of the game development process. Whether you’re working on the codebase or looking to understand the inner workings of the game, this hub provides a detailed guide to the systems, tools, and strategies used in the project.

---


