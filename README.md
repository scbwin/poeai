# PoEAI
## A Deep-Learning Based AI for Path of Exile

See [my blog series](https://nicholastsmith.wordpress.com/2017/07/08/a-deep-learning-based-ai-for-path-of-exile-a-series/) for more details on the individual components.

### Bot.py

The class that contains the main bot loop.

### BotDebugger.py

A class to help with debugging the main program.

### Main.py

Program entry point

### MovementMap.py

Class that keeps track of the bot's internal representation of the world. Contains a dictionary which maps 3D positions like (x,y,z) to a label (open, obstacle, item, etc).

### ProjMap.py

Handles converting from 3D to 2D coordinates and visa-versa based on a projection matrix calibrated for Path of Exile.

### ScreenViewer.py

Code to grab image data from the screen using Windows API

### TargetingSystem.py

Class for classifying image data from the game. Used to identify obstacles, enemies, items, and lightning warp (for movement).

### TFModel

Contains pre-trained tensorflow models
