Here is an updated README for your game:

---

# Rock Paper Scissors Gesture Detection Game

This project implements a Rock Paper Scissors game using hand gesture recognition. The player competes against the computer by making gestures that are detected via the camera, while the computer randomly chooses its own move.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Controls](#game-controls)
- [Known Issues](#known-issues)
- [License](#license)

## Features

- Uses **OpenCV** and **MediaPipe** to detect hand gestures via the camera.
- Recognizes **Rock**, **Paper**, and **Scissors** hand signs based on the number of fingers visible.
- The computer randomly selects a move, and the result is displayed after gesture detection.
- Fun and engaging messages for winning, losing, or tying.
- Easy replay functionality with Pygame GUI.

## Prerequisites

To run this project, you'll need the following installed:

- Python 3.x
- Pygame
- OpenCV (`opencv-python`)
- MediaPipe

You can install the required dependencies with:

```bash
pip install pygame opencv-python mediapipe
```

## Installation

1. Clone this repository or download the `.ipynb` file.
2. Open the **RockPaperScissor_GestureDetection_Final.ipynb** in Jupyter Notebook.
3. Ensure you have the required dependencies installed (listed in [Prerequisites](#prerequisites)).

## How to Play

1. Run the **RockPaperScissor_GestureDetection_Final.ipynb** notebook to start the game.
2. The game will open a Pygame window and your camera feed will appear.
3. After the "Get Ready" sequence, make a gesture in front of the camera:
   - **Rock**: Closed fist
   - **Paper**: Open hand with all fingers visible
   - **Scissors**: Two fingers visible (like a peace sign)
4. The computer randomly selects **Rock**, **Paper**, or **Scissors**, and the game will determine the winner.
5. Results will be displayed on the screen, including your choice and the computer’s choice.

## Game Controls

- **SPACE**: Replay the game after the result.
- **Q**: Quit the game at any time.

## Known Issues

- Hand detection may be inconsistent if the camera is not well-lit.
- Ensure your gestures are clear and well-positioned in front of the camera for better accuracy.
- Only the right hand can be used and the palm must always be facing the camera.

## License

This project is for educational purposes. Feel free to modify and distribute.

---

This README should cover the essentials for understanding and playing the game!
