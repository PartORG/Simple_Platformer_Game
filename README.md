# Simple_Platformer_Game

A simple example of a platformer game written in Python. Has a level editor as a separate code.

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)] [![License](https://img.shields.io/badge/license-MIT-green.svg)] [![Package Manager](https://img.shields.io/badge/package-manager-pip-yellow.svg)]

## Introduction

Welcome to Simple_Platformer_Game! This is a basic platformer game written in Python, designed for beginners and those looking to understand the fundamentals of game development. The project includes a level editor as a separate code, allowing you to create and edit levels easily.

The primary workflow involves running the game script `platformer.py` and using the level editor to design your own levels. This project is perfect for anyone interested in learning about game development, Python programming, or simply looking for a fun and engaging project to work on.

## Features

- **Simple Platformer Game**: A basic platformer game with various levels.
- **Level Editor**: A separate codebase for creating and editing levels.

## How It Works

The game is built using Python and includes the following components:

1. **Game Script (`platformer.py`)**: This script handles the main game logic, rendering, and user input.
2. **Image Files**: Various image files are used to represent different elements in the game, such as platforms, enemies, and collectibles.
3. **Level Data**: Each level is stored in a separate data file, allowing for easy creation and editing.

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python     | The programming language used for game development. |
| Pygame     | A set of Python modules designed for writing video games. |

## Requirements

- Python 3.x
- Pygame library (can be installed using `pip install pygame`)

## Installation

To install the required dependencies, run the following command:

```sh
pip install pygame
```

## Configuration

No specific configuration is required to run the game. Simply ensure that all image files and level data are in the correct directories.

## Quick Start

1. Clone the repository:
   ```sh
   git clone https://github.com/PartORG/Simple_Platformer_Game.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Simple_Platformer_Game
   ```
3. Run the game:
   ```sh
   python platformer.py
   ```

## Usage

To create and edit levels, you can use the level editor code. The exact usage instructions are not provided in this README, but you can refer to the source code for more details.

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

The development workflow involves editing the game script `platformer.py` and creating new levels in the data files. The project is open-source, so feel free to contribute by submitting pull requests or issues.

## Testing

No tests are included in this repository.

## Limitations

- The game is a simple example and may not be suitable for complex gameplay.
- No advanced features such as power-ups or enemies are implemented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.