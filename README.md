# AI-in-Game-Development

# AI-Powered NPC Game with Procedural Terrain

This project is an **AI-powered NPC movement simulation** built with **Pygame** and **TensorFlow**. The game features **procedurally generated terrain**, AI-controlled **NPCs**, and **obstacle avoidance**. It runs smoothly in **Google Colab** by capturing frames and generating a **GIF animation**.

##  Features
- 🏞 **Procedural Terrain Generation** using **Perlin Noise**.
- 🤖 **AI-driven NPC Movement** trained with **TensorFlow**.
- 🎭 **NPC Sprite Support** (or fallback to a default shape if unavailable).
- 🔥 **Obstacle Avoidance** to prevent NPCs from walking into blocked areas.
- 🎥 **GIF-based Animation** to visualize game progress in Google Colab.

## 🛠 Installation
This project is designed to run in **Google Colab**. If running locally, ensure you have **Python 3.11+**.

1️⃣ Install dependencies:
```sh
!apt-get update
!apt-get install -y python-opengl ffmpeg
!pip install pygame numpy tensorflow noise imageio requests
2️⃣ Clone this repository:
git clone https://github.com/your-username/AI-NPC-Game.git
cd AI-NPC-Game

3️⃣ Run the main.py script (or execute in Google Colab).

🏃‍♂️ Running in Google Colab
Since Google Colab does not support live Pygame rendering, the game:

Generates terrain and AI-driven NPC movement.
Saves multiple frames as images.
Creates a GIF animation for visualization.
To run the game in Google Colab:

from google.colab import files
files.upload()  # Upload main.py and required files

!python main.py

📜 How It Works
The AI model is trained to predict NPC movements.
The terrain is generated using Perlin noise.
NPCs move strategically, avoiding red obstacle areas.
A GIF is generated instead of real-time rendering.
📷 Expected Output
The final output will be an animated GIF showing NPCs moving intelligently across the procedural terrain.


📌 To-Do / Improvements
🔄 Add real-time keyboard controls for a player-controlled NPC.
🧠 Improve NPC AI using reinforcement learning.
🌍 Enhance terrain generation for more natural landscapes.
🎯 Implement pathfinding (A*) for smarter NPC movement.

👥 Duncan Kibet.

📜 License
This project is licensed under the MIT License.
