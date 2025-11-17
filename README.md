📖 About
Society 10 is an interactive strategy game where you take on the role of a national leader tasked with reducing inequality across four distinct societies: Urban, Rural, Tribal, and Minorities. Through careful decision-making, budget management, and strategic use of power-ups, you must balance the wellbeing of all communities while navigating economic crises, pandemics, protests, and opportunities.

Inspired by the United Nations' Sustainable Development Goal 10 (Reduced Inequalities), this game challenges players to think critically about policy decisions and their impact on different segments of society.

✨ Features
🎯 Core Gameplay
15 Turns of Strategic Decisions - Each turn presents unique events requiring careful consideration
4 Unique Societies - Manage Urban, Rural, Tribal, and Minority communities with different needs
Dynamic Event System - Over 5+ major events with multiple response options
Budget Management - Allocate limited resources wisely each turn
🌟 Special Features
🏆 10 Unlockable Achievements - Challenge yourself to unlock all achievements
⚡ Power-Up System - Use Equality Points to purchase game-changing power-ups
⏱️ Quick-Time Events - Rapid-response scenarios for bonus rewards
🎉 Special Events - Random celebrations and crises with unique animations
📰 Live News Ticker - Real-time updates on your policy decisions
🎨 Smooth Particle Effects - Visual feedback for actions and achievements
📊 Animated Statistics - Real-time bar graphs tracking society wellbeing
🎮 Enhanced UI/UX
Modern CustomTkinter interface with smooth animations
Color-coded visual feedback for positive/negative impacts
Responsive design with intuitive controls
Dark/Light mode support
🚀 Installation
Prerequisites
Before installing Society 10, ensure you have the following:

Python 3.8 or higher (Download Python)
pip (Python package installer - comes with Python)
Step 1: Clone the Repository
Bash

Step 2: Install Required Dependencies
Install all required Python packages using pip:

Bash

pip install customtkinter
pip install pillow
pip install pygame
Then add all these assets to a folder 📂 
Step 3: Add Assets (Optional)
For enhanced experience with sounds, add these files to the game directory:

button_click.mp3 - Button click sound effect
background_music.mp3 - Menu background music
victory_sound.mp3 - Victory celebration sound
loss_sting.mp3 - Game over sound
logo.png - Your logo/organization logo (60x60 pixels recommended)
Note: The game will run without these files, but audio features will be disabled.

Step 4: Run the Game
Bash

python society10.py
🎮 How to Play
Game Objective
Win Condition: Reach 100 Equality Points before Turn 15

Lose Conditions:

Equality Points drop to 0 or below
Any society's wellbeing falls below 10
National sentiment remains "Bad" for 3 consecutive turns
Game Mechanics
📊 Key Stats
Equality Points (EQ) - Your main score. Reach 100 to win!
Budget - Resets to 50 points each turn. Use it to implement policies.
Wellbeing - Each society has a wellbeing score (0-100)
Score - Tracks your overall performance
🎲 Turn Structure
Event Phase - A random event affects your nation
Decision Phase - Choose ONE response from 3 options
Effect Phase - Your choice impacts society wellbeing and Equality Points
Next Turn - Budget resets, societies drift slightly
💰 Budget System
Each response has a cost (shown on the card)
Higher cost = stronger impact
Budget resets to 50 each turn
Can't afford? Choose cheaper options or use Budget Surplus power-up
⚡ Power-Ups (Cost Equality Points)
Power-Up	Cost	Effect
🌟 Unity Boost	15 EQ	+10 wellbeing to ALL societies
💎 Budget Surplus	10 EQ	+50 extra budget this turn
🛡️ Crisis Shield	20 EQ	Halves the next crisis impact
⚡ Equality Surge	12 EQ	+15 Equality Points instant boost
🏆 Achievements
Unlock 10 achievements by accomplishing special feats:

👶 First Steps - Complete your first turn
⚖️ Balanced Act - Keep all societies above 60 wellbeing
🏆 Equality Champion - Reach 80 Equality Points
🚨 Crisis Manager - Successfully handle 3 crisis events
❤️ People's President - Win with all societies above 70
💰 Budget Master - Complete a turn without spending budget
🎲 Risk Taker - Choose the most expensive option 5 times
💪 Comeback Kid - Recover from below 20 Equality Points
⚡ Speed Runner - Win before turn 10
🌟 Perfectionist - Finish with all societies above 80
Strategy Tips 💡
Balance is Key - Neglecting any society leads to penalties
Help the Struggling - Raising low-wellbeing societies earns bonus points
Watch Your Budget - Don't overspend early; save for emergencies
Use Power-Ups Wisely - Save Crisis Shield for major disasters
Quick-Time Events - Fast decisions earn extra rewards
Special Events - Pay attention! These can be game-changers
Monitor Sentiment - 3 bad turns in a row = game over
🎯 Gameplay Controls
Action	Control
Choose Response	Click on "✅ Choose This" button
Use Power-Up	Click on desired power-up button
Next Turn	Click "➡️ Next Turn" (only after choosing response)
Return to Menu	Click "🏠 Return to Menu"
Quick-Time Event	Click "✅ Act Fast!" or "⏸️ Wait & See"
📦 File Structure
text

society-10/
│
├── gitignore.py           # Main game file      
├── README.md             # This file
├── logo.png              # logo (compulsory for the game to operate)
│
└── assets/ (optional)
    ├── button_click.mp3
    ├── background_music.mp3
    ├── victory_sound.mp3
    └── loss_sting.mp3
🛠️ Requirements
Python Packages
txt

customtkinter>=5.0.0
pillow>=9.0.0
pygame>=2.1.0
System Requirements
OS: Windows 10/11, macOS 10.14+, Linux (Ubuntu 20.04+)
RAM: 4GB minimum
Display: 1280x720 minimum resolution (1450x850 recommended)
Python: 3.8 or higher

🐛 Troubleshooting
Game won't start
Ensure Python 3.8+ is installed: python --version
Install all dependencies: pip install -r requirements.txt
Check for error messages in terminal
Logo not showing
Ensure logo.png is in the same folder as society10.py
Check image format (PNG recommended)
Verify image isn't corrupted
No sound
Install pygame: pip install pygame
Add sound files to game directory
Check system volume settings
Window too small/large
Edit geometry("1450x850") in code (line in PresidentialApp class)
Ensure minimum resolution: 1280x720
🤝 Contributing
Contributions are welcome! Here's how you can help:

Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
Ideas for Contributions
Add more events and scenarios
Create new achievements
Improve UI/UX
Add localization (multiple languages)
Create tutorial mode
Add more sound effects
Optimize performance
📝 License
This project is licensed under the MIT License - see below for details:

text

MIT License

Copyright (c) 2025 JS Works

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
🌟 Credits
Development
Company: JS Works
Game Design & Programming: Ashwin Sivakumar
Based on: UN Sustainable Development Goal 10 - Reduced Inequalities
Technologies Used
CustomTkinter - Modern UI framework
Pygame - Sound and audio
Pillow - Image processing
Python - Core programming language
Inspiration
United Nations Sustainable Development Goals
Political simulation games
Educational game design principles
