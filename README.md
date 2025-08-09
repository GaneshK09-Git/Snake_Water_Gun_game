Snake, Water, Gun - Game 🎮

A simple **Python command-line game** where you play Snake, Water, Gun against the computer.  
This is similar to Rock, Paper, Scissors, but with a twist.

How It Works:
- You choose **Snake (s)**, **Water (w)**, or **Gun (g)**.
- The computer makes a random choice.
- The winner is decided based on the rules:
- Snake 🐍 drinks Water 💧 → **Snake wins**  
- Water 💧 douses Gun 🔫 → **Water wins**  
- Gun 🔫 shoots Snake 🐍 → **Gun wins**
- If both choose the same, it's a draw.


Rules Mapping:
| Symbol | Choice  | Code Value |
|--------|---------|------------|
| `s`    | Snake   | 1          |
| `w`    | Water   | -1         |
| `g`    | Gun     | 0          |

---

How to Run:
1. Make sure you have **Python 3** installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/snake-water-gun.git
3. Navigate to the project folder:
cd snake-water-gun

4. Run the script:
python game.py

5. Enter your choice (s, w, or g) when prompted.


Example GamePlay:

Enter your choice: s

You chose Snake 

Computer chose Water

You win!

