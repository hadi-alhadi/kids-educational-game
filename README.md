# Kids Educational Game

## Overview
This educational game for kids is designed to provide a fun and interactive way to learn about different objects and their classifications into edible and non-edible categories. It utilizes the FaceMeshModule from cvzone to track the player's facial movements in real-time through a webcam. This technology allows the game to interact with the player by detecting when the mouth is opened wide enough to "eat" an object, making the gameplay immersive and interactive.

## How to Play
- The game presents objects moving across the screen, and the player must "eat" the correct ones by opening their mouth when an edible object is in front of them.
- The player's face is tracked in real-time, and the game detects when the mouth is opened wide enough to "eat" an object.
- Edible and non-edible objects are randomly generated and move down the screen. The player must avoid eating non-edible objects to continue playing.
- The score increases as the player successfully "eats" more edible objects.
- If a non-edible object is "eaten," the game ends, displaying a "Game Over" message.
- The player can restart the game by pressing the 'r' key.

## Requirements
- Python 3.x
- OpenCV
- cvzone

## Setup

1. Install the required Python packages using pip:
```bash 
pip install opencv-python-headless cvzone
```

2. Run the game by executing main.py script:
```bash
python main.py
```

3. Make sure you have a webcam connected and properly configured for the game to detect your facial movements.


## License
This project is licensed under the MIT License - see the LICENSE file for details.