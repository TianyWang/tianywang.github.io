---
title: "Tank Battle: the first shot when I learn Python"
# collection: fun-projects
date: 2025-12-31
excerpt: "A simple 2D tank battle game built with pygame, featuring AI-controlled enemies, destructible environments, and procedurally generated maps."
header:
  teaser: /images/tank-battle-screenshot.gif
---


## Game Overview

**Tank Battle** is a 2D game developed in **Python using pygame**.

The original idea for this game dates back to my early programming experience with **C++ and Microsoft Foundation Classes (MFC)**. At that time, I planned to build a tank battle game as a way to better understand **MFC window management**, **event-driven programming**, and **object-oriented design in C++**. However, the complexity of UI boilerplate and memory management made rapid prototyping challenging.

After transitioning to **Python**, I realized that the same core game logic and object-oriented structure could be implemented in a **much more concise and readable way**. As a result, I rebuilt the tank battle concept using pygame during my Python learning phase, allowing me to focus more on **game mechanics, enemy behavior, and system design**, rather than low-level framework details.

This project therefore reflects both my **early interest in coding with C++** and my later appreciation of **Python as an efficient tool for rapid development and experimentation**.

## Key Features

- **AI Enemy Behavior**
  - Enemies switch between *patrolling* and *player-tracking* modes
  - Line-of-sight detection and distance-based engagement
  - Autonomous firing logic with cooldown control

- **Destructible Environment**
  - Walls can be damaged and destroyed by tank shells
  - Terrain dynamically changes during gameplay

- **Procedurally Generated Maps**
  - Randomized wall layouts for each run
  - Ensures replayability and varied combat scenarios

- **Projectile & Collision System**
  - Real-time bullet physics
  - Accurate collision detection between tanks, walls, and projectiles

## Screen Shot

![Tank Battle Screenshot](/images/tank-battle-screenshot.gif)
