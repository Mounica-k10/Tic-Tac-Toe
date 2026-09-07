# Tic-Tac-Toe

This is a simple Tic-Tac-Toe game developed using **HTML, CSS, and JavaScript**. The game can be played either against the computer or with another player.

The main focus of this project was to create a simple and interactive game interface using HTML and CSS and implement the game functionality using JavaScript.

## Features

* One Player mode to play against the computer
* Two Player mode for playing with another person
* 3 × 3 Tic-Tac-Toe board
* Displays the current player's turn
* Checks for a winner after every move
* Detects a draw when all the boxes are filled
* Simple and easy-to-use interface

## Game Modes

### One Player

In One Player mode, the user plays against the computer.

The player makes a move by selecting an empty box, and the computer automatically makes its move after that.

### Two Player

In Two Player mode, two players can play on the same device.

* Player 1 plays as **X**
* Player 2 plays as **O**

The game changes the turn between the two players after each move.

## How the Game Works

The game board contains 9 boxes arranged in a 3 × 3 layout.

When a player selects a box, the move is recorded and the game checks the possible winning combinations.

A player wins when the same symbol appears in:

* Any row
* Any column
* The main diagonal
* The opposite diagonal

If all the boxes are filled and no player has a winning combination, the game ends in a draw.

## Technologies Used

* **HTML5** – Used to create the structure of the game.
* **CSS3** – Used to design the game board, buttons, text, and overall layout.
* **JavaScript** – Used to implement the game logic, player moves, computer moves, turn changes, winner checking, and draw detection.

## Project Structure

```text
Tic-Tac-Toe/
│
├── project.html
├── project.css
├── project.js
└── .vscode/
    └── settings.json
```

### project.html

Contains the structure of the webpage, including the game mode selection and Tic-Tac-Toe board.

### project.css

Contains the styling of the game, including the board layout, buttons, text, and overall appearance.

### project.js

Contains the main functionality of the game, such as:

* Selecting the game mode
* Handling player moves
* Handling computer moves
* Changing turns
* Checking winning conditions
* Checking for a draw
* Updating the game status

## How to Run the Project

1. Download or clone the project.
2. Open the project folder in VS Code.
3. Open `project.html` in a web browser.

You can also use the **Live Server** extension in VS Code to run the project.

## How to Play

1. Open the game in a browser.
2. Select either **One Player** or **Two Player** mode.
3. Click on an empty box to make a move.
4. In One Player mode, the computer will make its move automatically.
5. Continue playing until a player wins or the game ends in a draw.

## Conclusion

This Tic-Tac-Toe project helped in understanding the basics of **HTML, CSS, and JavaScript** by combining them to create an interactive game. It also helped in understanding concepts such as user interactions, game logic, conditional statements, and handling events in JavaScript.
