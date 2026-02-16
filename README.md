
# Project Title

A brief description of what this project does and who it's for

# 🎰 Terminal Slot Machine Game

Welcome to a simple yet thrilling **Slot Machine Game** built using **Node.js**!  
This was inspired by [this awesome tutorial](https://youtu.be/E3XxeE7NF30?si=84qpXYr_h9UMBxUb) by `Web Dev Simplified` and modified a bit to improve functionality and clarity. 💡

---

## 🎮 Features

- 💸 Deposit money to play  
- 🎯 Choose how many lines you want to bet on (1 to 3)  
- 🎲 Place your bet per line  
- 🎰 Spin the reels  
- 🏆 Win based on matching symbols  
- 🔁 Option to play again until balance runs out  

---

## 📦 Requirements

- [Node.js](https://nodejs.org/en/) installed on your machine

---

## 🛠️ How to Run

1. **Clone the repository** 📁


git clone https://github.com/your-username/slot-machine-game.git

cd slot-machine-game

2. **Install dependencies (only needed if not using global packages)**

npm install
💡 This game uses prompt-sync to take user input in the terminal.If not installed globally, install it using:

npm install prompt-sync

3. **Run the game 🕹️**

node project.js

📸 Preview
Enter the deposit amount: 1000

Your balance is $1000

Enter the number of lines to bet on (1-3): 3

Enter the bet per line: 50

🎰 D | D | C

🎰 D | D | C

🎰 B | B | B

You won, $150

Do you want to play again? (y/n):

**🧠 Symbols & Values**

Symbol	Frequency	Value

A	Rare	5x

B	Uncommon	4x

C	Common	3x

D	Very Common	2x

**✨ Modifications I Made**

🔄 Cleaned up row printing using .join(" | ")

🧼 Improved error handling and user prompts

✅ Added input validation and clear messages

**🙏 Credits**

👨‍🏫 Web Dev Simplified's slot machine tutorial

**🚀 Future Plans**

🌟 Add player leaderboard

💾 Save game history

🎨 Convert to a GUI version using Electron

🔊 Add sounds and emoji-based reels for more fun

**🤝 Let's Connect**

If you're also learning Node.js or building CLI games, drop a ⭐, fork the repo, or reach out!
Let’s keep leveling up together 💻🚀🎨
