The Infinite Dungeon

The Infinite Dungeon is an AI-powered, text-based RPG adventure game that brings classic tabletop role-playing elements into a dynamic, procedurally generated digital world. You, the player, navigate through endless dungeons, face encounters, collect treasures, and shape your fate — all guided by an intelligent, GPT-powered Dungeon Master.

⚔️ Explore. 🧠 Choose. 🎭 Roleplay. Repeat.

🌟 Features
•	🎮 Interactive Text-Based RPG: Navigate a mysterious dungeon using simple text inputs.
•	🧙‍♂️ AI-Powered Dungeon Master: A GPT-based Dungeon Master dynamically generates story elements and responses.
•	🗺️ Procedural World Generation: No two runs are the same — explore infinite rooms, paths, and events.
•	🎒 Player State Management: Health, inventory, and choices persist and affect gameplay.
•	💾 Save & Load Game: Continue your adventure right where you left off.

🚀 Getting Started
1.	📦 Requirements
•	Python 3.7 or higher
•	`openai` Python library
•	Optional: `Flask` or `Streamlit` for web-based UI
2.	🔧 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/siddhantp011/The-Infinite-Dungeon.git
cd The-Infinite-Dungeon
pip install -r requirements.txt
```
3.	🔑 OpenAI API Key
To enable AI responses, set your OpenAI API key as an environment variable:
```bash
export OPENAI_API_KEY="your-api-key"
```
▶️ How to Play
Start the game:
```bash
python main.py
```
Then enter commands like:
•	> look around
•	> open the door
•	> attack the goblin
•	> use health potion
🎮 Sample Gameplay
DM: You awaken in a damp, torch-lit chamber. There are doors to the north and east.
You: I open the north door.
DM: The door creaks open, revealing a long hallway. At the far end, a glowing rune pulsates on the wall.
You: I walk towards the rune.
DM: As you approach, the rune hums louder. Suddenly, the floor gives way beneath your feet!
📁 Project Structure
•	main.py               # Entry point for the game
•	game_engine.py        # Core logic and state management
•	ai_dungeon_master.py  # GPT-driven story generation
•	save_load.py          # Save/load functionality
•	requirements.txt      # List of Python dependencies
•	README.md             # Project overview
•	.env (optional)       # For storing the OpenAI API key securely
🛠️ Technologies Used
•	Python 3 for game logic and interface
•	OpenAI GPT API for story generation
•	Optional: Flask / Streamlit for building a web interface
•	dotenv for managing environment variables
🚧 Roadmap
•	Combat system with dice mechanics
•	Map and visual dungeon navigation
•	Web-based UI (Flask/Streamlit)
•	Voice command input (STT)
•	Character classes and leveling
•	World generation and quests
🤝 Contributing
We welcome contributions, feature suggestions, and bug reports!

To contribute:
1. Fork the repo
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m 'Add your feature'`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request
📫 Connect with the Developer
🧑‍💻 Siddhant Ojha
🌐 GitHub: https://github.com/siddhantp011
💼 LinkedIn: https://www.linkedin.com/in/siddhant-ojha-27b59021a/
🛡️ License
This project is licensed under the MIT License. See the LICENSE file for details.
“In the shadows of the dungeon, your story awaits. Dare to enter?”
