# stone_paper_scissors

✂️ Stone Paper Scissors Game
A fun and interactive implementation of the classic Stone Paper Scissors game, where players compete against the computer. This project demonstrates basic programming concepts like conditionals, loops, randomization, and user input handling. Perfect for beginners learning programming or game logic.

🎮 Features
Simple and intuitive user interface (CLI or GUI)
Player vs Computer gameplay
Randomized computer moves using a pseudo-random generator
Real-time round result: Win / Lose / Draw
Game continues until user exits
Optional:
    Scoreboard to track wins, losses, and draws
    Sound effects or animations (if GUI)
    Responsive GUI (if using HTML/CSS/JS or Python + Tkinter/PyQt)

⚙️ Game Logic
Player selects: Stone, Paper, or Scissors
Computer randomly selects one of the three
Result is decided based on standard rules:

Player →      Computer ↓      	Result
Stone          Scissors	        Player Wins
Stone	         Paper	          Computer Wins
Paper          Stone            Player Wins
Paper       	 Scissors	        Computer Wins
Scissors	     Paper	          Player Wins
Scissors	     Stone	          Computer Wins
Same       	   Same	            Draw


🧠 Rules
Stone beats Scissors
Scissors beats Paper
Paper beats Stone
If both choices are the same, it's a Draw



🕹 How to Play
*Run the program
*Choose your move: Stone, Paper, or Scissors
*Wait for the computer to make its move
*View the result (Win/Loss/Draw)
*Continue playing or exit the game


📸 Example Output (CLI)
Choose (stone/paper/scissors): stone
Computer chose: scissors
Result: You WIN! 🏆


🛠 Tech Stack
Language/frameworks used
Optional UI libraries or tools



🧱 Technologies Used:

Python 3.x (or other: JavaScript, HTML/CSS, Java, etc.)

random module for move generation

input() or GUI input for player choice

Optional:  tkinter/pygame/React/Vue for graphical interface



🚧 Future Enhancements:

Score tracking for multiple rounds

Add multiplayer mode (local or networked)

Add timer for quick decision-making

Add difficulty levels (computer with prediction)

Deploy as web application or mobile app

