## **Pong game**

### **Project Description**

This Python project implements a classic Pong game using the Turtle graphics library. Where 2 players control the one paddle on each side of the screen to stop the ball from going behind there paddle and giving the other player 1 point, the ball speeds increase the longer the game goes on.

### **Getting Started**

1. **Prerequisites:**
    * Python 3.x installed
    * `turtle` library (usually comes pre-installed with Python)

2. **Installation:**
    * Clone this repository or download the Python files (`main.py`, `ball.py`, `scoreboard.py`, `paddle.py`).

3. **Usage:**
    * Navigate to the project directory in your terminal.
    * Run the `main.py` file: `python main.py`

### **Gameplay**

* Two players compete in a classic Pong game.
* Players control paddles on either side of the screen using the keyboard.
* The objective is to prevent the ball from passing behind your paddle, awarding a point to the opponent.
* The ball bounces off the top and bottom walls of the game screen.
* Collision with the paddles deflects the ball and increases its speed slightly for added difficulty.

### **Project Structure**

* **main.py:** The main script that initializes the game environment, creates objects (paddles, ball, scoreboard), and manages the game loop.
* **ball.py:** Defines the `Ball` class responsible for ball movement, collision detection with walls and paddles, and bouncing behavior.
* **scoreboard.py:** Defines the `Scoreboard` class that tracks player scores and displays them on the screen.
* **paddle.py:** Defines the `Paddle` class that handles the movement of the paddles based on user input.

### **Keyboard Controls**

* Player 1 (Right Paddle):
    * Up Arrow: Move Paddle Up
    * Down Arrow: Move Paddle Down
* Player 2 (Left Paddle):
    * W Key: Move Paddle Up
    * S Key: Move Paddle Down

### **Dependencies**

This project relies on the `turtle` library, which is part of the standard Python library.

Link to the turtle documentation: https://docs.python.org/3/library/turtle.html

**Enjoy playing your Pong game!**
