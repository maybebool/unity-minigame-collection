# Unity Mini Games

[![Unity](https://img.shields.io/badge/Unity-2021.3+-000000?style=flat-square&logo=unity&logoColor=white)](https://unity.com/)
[![C#](https://img.shields.io/badge/C%23-MonoBehaviour-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Games](https://img.shields.io/badge/Games-13_Implementations-FF6F61?style=flat-square)](https://github.com/maybebool/UnityMiniGames)
[![Level](https://img.shields.io/badge/Level-Beginner_▸_Intermediate-77B829?style=flat-square)](https://github.com/maybebool/UnityMiniGames)

13 classic mini games implemented in Unity from scratch — designed as a hands-on reference for game development students learning core mechanics, algorithms, and data structures.

## Objective

Provide a self-contained collection of well-known game implementations that cover the fundamental patterns encountered in game development exams and entry-level projects. Each game focuses on the core mechanic rather than visual polish, making the underlying logic easy to study and reproduce. The repository is intended as a rebuild-it-yourself exercise: attempt each game from scratch and use this repo as a reference when stuck.

## Learning Outcomes

| Topic | Covered By |
|:---|:---|
| Game loops & state machines | Tetris, Minesweeper, Tic Tac Toe |
| 2D physics & collision | Asteroids, Breakout, Pong, Flappy Bird |
| Grid-based logic | Minesweeper, Tetris, Snake, Tic Tac Toe |
| Spawning & object pooling | Bubble Shooter, Space Invaders, Fruit Ninja |
| Input handling & movement | All 13 games |
| Coroutines & timing | Snake, Tetris, Doodle Jump |
| Canvas UI & Prefabs | Pause menu, Game Over/Won panels in every game |
| Simple AI | Pong (computer-controlled opponent) |

## Games & Controls

Every game includes a Pause Menu (`Esc`) and a Game Over / Won panel.

| # | Game | Controls | Core Mechanic |
|:---:|:---|:---|:---|
| 1 | Asteroids | `WASD` move · `Space` shoot | Wraparound movement, projectile spawning |
| 2 | Breakout | `←` `→` move | Ball reflection angles, brick destruction |
| 3 | Bubble Shooter | `LMB` shoot | Grid snapping, flood-fill matching |

<p align="center">
  <img src="Recordings/Image%20Sequence_003_0005.jpg" alt="Asteroids" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_004_0005.jpg" alt="Breakout" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_006_0005.jpg" alt="Bubble Shooter" height="180">
</p>
<p align="center"><em>Asteroids · Breakout · Bubble Shooter</em></p>

| # | Game | Controls | Core Mechanic |
|:---:|:---|:---|:---|
| 4 | Doodle Jump | `A` `D` move | Procedural platform generation, vertical scrolling |
| 5 | Flappy Bird | `Space` jump | Gravity, gap collision, score gating |
| 6 | Fruit Ninja | `LMB` hold + mouse move | Swipe detection, fruit slicing physics |

<p align="center">
  <img src="Recordings/Image%20Sequence_007_0005.jpg" alt="Doodle Jump" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_008_0005.jpg" alt="Flappy Bird" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_009_0005.jpg" alt="Fruit Ninja" height="180">
</p>
<p align="center"><em>Doodle Jump · Flappy Bird · Fruit Ninja</em></p>

| # | Game | Controls | Core Mechanic |
|:---:|:---|:---|:---|
| 7 | Minesweeper | `LMB` click | Recursive flood reveal, mine adjacency counting |
| 8 | Tetris | `A` `D` move · `Q` `E` rotate | Piece rotation matrices, line clearing |
| 9 | Tic Tac Toe | `LMB` click | Win-condition checking, turn management |

<p align="center">
  <img src="Recordings/Image%20Sequence_010_0005.jpg" alt="Minesweeper" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_015_0005.jpg" alt="Tetris" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_017_0005.jpg" alt="Tic Tac Toe" height="180">
</p>
<p align="center"><em>Minesweeper · Tetris · Tic Tac Toe</em></p>

| # | Game | Controls | Core Mechanic |
|:---:|:---|:---|:---|
| 10 | Pong | `W` `S` move | Ball physics, simple AI opponent |
| 11 | Snake | `WASD` move | Linked-list body, grid-based growth |
| 12 | Space Invaders | `A` `D` move · `Space` shoot | Formation movement, projectile collision |

<p align="center">
  <img src="Recordings/Image%20Sequence_011_0005.jpg" alt="Pong" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_012_0005.jpg" alt="Snake" height="180">
  &nbsp;&nbsp;
  <img src="Recordings/Image%20Sequence_013_0005.jpg" alt="Space Invaders" height="180">
</p>
<p align="center"><em>Pong · Snake · Space Invaders</em></p>

| # | Game | Controls | Core Mechanic |
|:---:|:---|:---|:---|
| 13 | Space Wars | `W` `S` move · `LMB` shoot | Side-scrolling combat, enemy wave spawning |

<p align="center">
  <img src="Recordings/Image%20Sequence_014_0005.jpg" alt="Space Wars" height="180">
</p>
<p align="center"><em>Space Wars</em></p>


## Getting Started

```bash
git clone https://github.com/maybebool/UnityMiniGames.git
```

1. Open the project in Unity 2021.3+.
2. In the Project window, navigate to `Assets/Scenes/`.
3. Double-click any scene to open a game.
4. Press Play.

**Prerequisites:** Unity 2021.3+.

## Tech Stack

[![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)](https://unity.com/)
[![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)

| Category | Technology |
|:---|:---|
| Engine | Unity 2021.3+ |
| Language | C# (MonoBehaviour, Coroutines) |
| Rendering | Unity 2D, Sprite Renderer, Canvas UI |
| Input | Unity Input System (keyboard + mouse) |

## Limitations & Future Work

The focus is on core mechanics rather than visual polish. Possible extensions include:

- Visual overhaul with consistent art style across all 13 games
- High-score persistence using `PlayerPrefs` or JSON serialisation
- Difficulty scaling (adaptive enemy speed, shrinking paddles, faster drops)
- Mobile touch input for deployment on Android / iOS
- Menu hub scene with game selection and progress tracking
- Additional games (Pac-Man, Connect Four, 2048, Sudoku)
