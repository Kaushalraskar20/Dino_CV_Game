# 🦖 Gesture-Controlled Dino Game
A modern remake of the classic Chrome Dino game, controlled using hand gestures detected through a webcam.
This project uses MediaPipe, OpenCV, and Pygame to enable real-time gesture recognition for gameplay.

🎮 Gameplay Overview
Instead of keyboard controls, this Dino game responds to hand gestures:
| Gesture                         | Action                  |
| ------------------------------- | ----------------------- |
| ☝️ One finger (Index)           | Jump                    |
| ✌️ Two fingers (Index + Middle) | Duck                    |
| 🖐️ Open palm (4+ fingers)      | Restart after Game Over |
| No hand detected                | Normal running          |

🧠 How It Works

1.Webcam input is captured using OpenCV
2.MediaPipe Hand Landmarker detects finger positions
3.Gestures are mapped to game actions (jump / duck / restart)
4.Pygame handles rendering, physics, obstacles, and scoring
5.The Dino and obstacles are rendered using ASCII-style sprites and emojis for a lightweight, minimal look


🛠️ Technologies Used

1.Python 3.9+
2.OpenCV
3MediaPipe
4.Pygame

