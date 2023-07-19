# Pong Game
Welcome to the Pong game! This classic Pong game is developed using Python's Turtle library, allowing you to play against a friend. The objective is to bounce the ball off the paddles and score points by getting the ball past your opponent's paddle.

## How to Play
<b>Install Python:</b> Make sure you have Python installed on your computer. If not, download and install the latest version from the official Python website (https://www.python.org/downloads/).

<b>Clone the Repository:</b> Clone or download the repository to your local machine.

<b>Run the Game:</b> Navigate to the directory where the files are located and run the "main.py" file using Python. This will launch the game window, and you can start playing Pong.

<b>Game Rules:</b> 
<ul>
    <li>Before the game starts, you will be prompted to enter the maximum score you want to play to.</li>
    <li>Player I controls the left paddle using the "q" key to move up and the "x" key to move down.</li>
    <li>Player II controls the right paddle using the "P" key to move up and the "M" key to move down.</li>
    <li>The ball's speed increases after each point scored, adding a challenge to the game.</li>
    <li>Use your paddle to hit the ball and bounce it back toward your opponent's side.</li>
    <li>Score points by getting the ball past your opponent's paddle.</li>
    <li>The game ends when one player reaches the maximum score set at the beginning.</li>
</ul>

<b>Controls:</b>
<ul>
    <li>Left Paddle: Use the "q" key to move up and the "x" key to move down.</li>
    <li>Right Paddle: The right paddle is controlled by the AI and automatically follows the ball.</li>
</ul>

<b>Scoring:</b> 
<ul>
    <li>The score is displayed at the top of the screen for both players.</li>
    <li>Each time a player scores a point, their respective score is updated.</li>
    <li>The ball's speed increases after each point scored, making the game more challenging.</li>
</ul>

<b>Game over:</b> 
<ul>
    <li>The game ends when one of the players reaches the maximum score set at the beginning.</li>
    <li>A message will be displayed on the screen announcing the winner.</li>
</ul>

## Files Overview
<b>main.py:</b> This is the main file that launches the Pong game. It sets up the game window, creates instances of the Ball, Paddle, MiddleLine, ScoreBoard, and GameOver classes, handles user input, and controls the game loop.

<b>ball.py:</b> This file contains the Ball class, which represents the ball in the Pong game. It handles the ball's movement, bouncing off the paddles, and resetting its position. The ball's speed increases after each point scored.

<b>paddles.py:</b> This file contains the Paddle and MiddleLine classes. The Paddle class represents the left and right paddles, and the MiddleLine class draws the middle line on the game board.

<b>scoreboard.py:</b> This file contains the ScoreBoard and GameOver classes. The ScoreBoard class manages the players' scores, while the GameOver class displays the winner's message when the game ends.

Have fun playing Pong with your friend! If you have any suggestions or feedback, feel free to contribute or reach out to me. Enjoy!