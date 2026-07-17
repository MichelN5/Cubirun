# Cubirun

A simple 3D obstacle-running game built with **Unity** and **C#**.

The player controls a blue cube moving across a platform and must avoid the obstacles placed along the course. The score increases as the run continues, making the objective simple: stay on the platform, avoid collisions, and achieve the highest score possible.

![Cubirun gameplay](docs/cubirun-gameplay.jpg)

## Gameplay

- Control a cube moving through a 3D obstacle course
- Move sideways to avoid incoming obstacles
- Stay on the platform and avoid falling
- Continue running to increase your score
- Restart and try to beat your previous result

## Built With

- Unity
- C#
- Unity physics and collision system
- Unity UI for the score display

## Getting Started

### Requirements

- Unity Hub
- A compatible Unity Editor version

### Run the project

1. Clone the repository:

```bash
git clone https://github.com/MichelN5/Cubirun.git
cd Cubirun
```

2. Open Unity Hub.
3. Select **Add project from disk**.
4. Choose the cloned project folder.
5. Open the main game scene.
6. Press the **Play** button in the Unity Editor.

Unity Hub should suggest installing the required editor version when it reads the project configuration.

## Project Structure

A Unity project normally keeps its source-controlled files in these directories:

```text
Assets/          Game scenes, scripts, materials, prefabs, and other assets
Packages/        Unity package configuration
ProjectSettings/ Unity project and editor settings
```

Generated Unity directories such as `Library`, `Temp`, `Logs`, `Build`, and `UserSettings` are excluded from version control.

## Project Scope

Cubirun is a small learning project focused on fundamental Unity concepts:

- Player movement
- Physics and collisions
- Obstacle placement
- Camera positioning
- Score tracking
- Basic 3D level design

## Author

Developed by [Michel Naouss](https://github.com/MichelN5).