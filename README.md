# 🐍💧🔫 Snake Water Gun: Terminal Edition

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg?style=flat-square&logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)

A highly polished, interactive Command Line Interface (CLI) version of the classic **Snake-Water-Gun** game. 

This project goes beyond a simple loop by integrating cross-platform OS handling, rich ANSI terminal colors, and persistent session statistics to deliver a seamless user experience entirely within the terminal.

---

## 📸 Game Preview
*(Note: Upload a screenshot of your game running in the terminal to your GitHub repository and link it here to make this section pop!)*

---

## ✨ Features

* **Cross-Platform Compatibility:** Utilizes Python's native `os` module to automatically detect the operating system and manage terminal clearing (`cls` for Windows, `clear` for Unix) without external dependencies.
* **Dynamic State Management:** Accurately tracks round-by-round scores, ties, and live winning streaks for both the player and the computer.
* **Rich Terminal UI:** Implements ANSI escape codes to render beautifully color-coded text, improving readability and engagement.
* **Suspense Mechanics:** Features a timed, animated `.` countdown during the computer's turn to simulate decision-making.
* **Robust Input Handling:** Recursively traps invalid inputs, ensuring the game loop never crashes due to a typo.
* **Session Analytics:** Concludes the game with a statistical breakdown, calculating overall win-rate percentages and maximum streaks.

---

## 🎮 Game Rules

The mechanics are similar to Rock-Paper-Scissors:
1. **Snake 🐍 vs. Water 💧** ➔ Snake drinks the water. **(Snake Wins)**
2. **Water 💧 vs. Gun 🔫** ➔ Water damages the gun. **(Water Wins)**
3. **Gun 🔫 vs. Snake 🐍** ➔ Gun defeats the snake. **(Gun Wins)**

---

## 🚀 Installation & Usage

### Prerequisites
* Python 3.x installed on your machine.

### Run Locally
To run this game on your own computer, open your terminal and run the following commands:

1. Clone the repository:
   `git clone https://github.com/YourUsername/snake-water-gun-cli.git`

2. Navigate to the directory:
   `cd snake-water-gun-cli`

3. Execute the script:
   `python main.py`

---

## 🛠️ Under the Hood

This project was built to demonstrate clean scripting and fundamental software engineering principles in Python:

* **Modular Functions:** Logic is strictly separated into helper functions (`determine_winner`, `get_user_choice`, `countdown`) to keep the main game loop clean.
* **Dictionary Mapping:** Uses efficient dictionary lookups for user inputs and reversed mappings for displaying the computer's choice.
* **Zero Dependencies:** Built entirely using Python Standard Libraries (`random`, `time`, `os`).

---

## 👤 Author
**Andreyas**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/eng-Andreyas)

[![GitHub](https://img.shields.io/badge/GitHub-View_Projects-lightgrey?style=flat-square&logo=github)](https://github.com/andreyas-dev)

---
*If you enjoyed this project, please consider giving it a ⭐!*
