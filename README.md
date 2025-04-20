Dice Game - Python Console Project:
This is a simple command-line dice game written in Python for 1 to 4 players. 
Each player takes turns rolling a die, and the first to reach or exceed **50 points** wins the game. 
If you roll a **1**, your turn ends and you lose all points from that turn.

Features:
- Supports **1 to 4 players**
- Turn-based gameplay
- Random dice rolls (1 to 6)
- Ends when a player hits **50 points**
- Simple input validation and instructions

How to Run:
1. Make sure you have **Python 3** installed.
2. Clone this repo or copy the code into a file named `dice_game.py`.
3. Run it using your terminal:

```bash - python dice_game.py

🎮 Game Rules____________________________________________________________________________
1. Each player starts with 0 points.
2. On your turn, you can choose to roll or hold.
3. If you roll a 1, your turn ends and you lose the points gained in that turn.
4. Any other roll (2–6) adds to your turn score.
5. You can keep rolling to accumulate more, or hold to add the turn score to your total score.
6. First player to reach 50 total points wins!

📸 Preview________________________________
Enter the number of players (1-4): 2

Player number 1 turn has just started!
Your total score is: 0

Would you like to roll (y)? y
You rolled a: 4
Your score is: 4


📦 Requirements___________________________________
1. Python 3.x
2. No external libraries required (only uses random)

💡 Ideas for Improvement___________________________
# Add player names
# Add score history or a scoreboard
# GUI version using Tkinter or Pygame
# Multiplayer over network******
