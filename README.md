# Car Dodger 🚗

A 2D arcade game built with **OpenGL (GLUT)** as a computer graphics practical project. Dodge oncoming cars, collect coins, and survive the timer!

## Features

- **Three lanes** of traffic with randomly spawning enemy cars
- **Timed rounds** (5s / 10s / 30s) or **Infinite Mode**
- **Coin collection** — spend 5 coins to continue after a crash
- **Win condition** — survive the timer without crashing
- **Controls** — keyboard (`A`/`D`) or mouse buttons while playing
- **Polished UI** — gradient backgrounds, rounded buttons, animated road markings

## How to Play

1. **Main Menu** — pick a duration (or Infinite) to start
2. **During the game** — switch lanes to dodge red/yellow/purple cars
3. **Collect coins** (gold circles) to build up your continue budget
4. **Crash?** — spend 5 coins to continue, or return to menu
5. **Win** — survive the clock and see your final score

## Controls

| Key | Action |
|-----|--------|
| `A` / `D` | Move left / right |
| Mouse click | Click lane buttons or UI buttons |
| `1`–`4` | Quick-start from menu (1=5s, 2=10s, 3=30s, 4=Infinite) |

## Building

- **IDE:** Visual Studio (`.sln` / `.vcxproj` provided)
- **Dependency:** [freeglut](https://freeglut.sourceforge.net/) (MSVC link: `freeglut.lib`)
- Open `ConsoleApplication1.sln`, set **x64 | Debug**, and build.

> The `x64/Debug/` folder contains a pre-built `.exe` with `freeglut.dll` — you can run it directly on Windows.

## Project Structure

```
├── ConsoleApplication1.cpp   # Full game source (~576 lines)
├── ConsoleApplication1.sln   # Visual Studio solution
├── ConsoleApplication1.vcxproj / .filters / .user
├── x64/Debug/                # Pre-built binary
└── README.md
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/93643aec-7201-40a8-8e09-236e4d57d722" width="45%" />
  <img src="https://github.com/user-attachments/assets/99b5dfb5-5ac9-4bef-955a-7fa4b3a6014a" width="45%" />
</p>










Built with 💙 for the Computer Graphics course.
