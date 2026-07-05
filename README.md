# Simple_Platformer_Game

A simple example of a platformer game written in Python. Has a level editor as a separate code.

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)] [![License](https://img.shields.io/badge/license-MIT-green.svg)] [![Package Manager](https://img.shields.io/badge/package-manager-pip-orange.svg)] [![Framework](https://img.shields.io/badge/framework-Pygame-red.svg)]

## Introduction

Simple_Platformer_Game is a basic platformer game written in Python using the Pygame framework. It includes a level editor to create and edit levels, making it an excellent starting point for learning game development with Python.

The primary workflow involves creating levels using the level editor, which then can be played within the game. The main advantages of this project include its simplicity, ease of use, and the ability to learn game development fundamentals through practical implementation.

## Table of Contents

1. [Features](#features)
2. [How It Works](#how-it-works)
3. [Technology Stack](#technology-stack)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Configuration](#configuration)
7. [Quick Start](#quick-start)
8. [Usage](#usage)
9. [Project Structure](#project-structure)
10. [Development](#development)
11. [Limitations](#limitations)
12. [License](#license)

## Features

### Level Editor

The level editor allows users to create and edit levels for the platformer game. It provides a simple interface to place various elements like platforms, enemies, and collectibles.

### Playable Game

Once levels are created using the level editor, they can be played within the game. The player controls a character that must navigate through the levels, collecting items and avoiding obstacles.

## How It Works

The platformer game is built using the Pygame framework in Python. The architecture consists of two main components: the game engine and the level editor.

### Game Engine

The game engine handles the rendering of the game world, player input, collision detection, and game logic. It uses Pygame's event handling system to manage user inputs and update the game state accordingly.

### Level Editor

The level editor is a separate application that allows users to create levels for the platformer game. It provides a graphical interface where users can drag and drop elements like platforms, enemies, and collectibles onto a canvas.

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python     | The programming language used to develop the game. |
| Pygame     | A set of Python modules designed for writing video games. |
| ASCII Diagrams | Used in the README to illustrate the architecture of the game. |

## Requirements

To run this project, you need:

- Python 3.x
- Pygame library (can be installed using pip)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/PartORG/Simple_Platformer_Game.git
   ```

2. Navigate to the project directory:
   ```sh
   cd Simple_Platformer_Game
   ```

3. Install the required dependencies:
   ```sh
   pip install pygame
   ```

## Configuration

No configuration files or environment variables are required for this project.

## Quick Start

1. Run the game:
   ```sh
   python platformer.py
   ```

2. Use the level editor to create a new level by running:
   ```sh
   python level_editor.py
   ```

## Usage

### Game Play

- **Controls**: Use the arrow keys to move the player left and right, jump with the spacebar.
- **Objective**: Collect all collectibles and reach the exit.

### Level Editor

- **Adding Elements**: Drag and drop platforms, enemies, and collectibles onto the canvas.
- **Saving Levels**: Click the "Save" button to save your level data.

## Project Structure

```
Simple_Platformer_Game/
├── .gitignore
├── img/
│   ├── blob.png
│   ├── coin.png
│   ├── coin.wav
│   ├── dirt.png
│   ├── exit.png
│   ├── exit_btn.png
│   ├── game_over.wav
│   ├── ghost.png
│   ├── grass.png
│   ├── guy1.png
│   ├── guy2.png
│   ├── guy3.png
│   ├── guy4.png
│   ├── jump.wav
│   ├── lava.png
│   ├── load_btn.png
│   ├── music.wav
│   ├── platform.png
│   ├── platform_x.png
│   ├── platform_y.png
│   ├── restart_btn.png
│   ├── save_btn.png
│   ├── sky.png
│   ├── start_btn.png
│   └── sun.png
├── level0_data
├── level1_data
├── level2_data
├── level3_data
├── level4_data
├── level5_data
├── level6_data
├── level7_data
└── platformer.py
```

## Development

The development workflow involves:

1. Editing the `platformer.py` file to add new features or fix bugs.
2. Using the level editor (`level_editor.py`) to create and test levels.

## Limitations

- The game is a simple example and lacks advanced features like power-ups, enemies with AI, or complex level designs.
- There are no tests included in this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.