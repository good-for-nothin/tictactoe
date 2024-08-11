# Tic-Tac-Toe Game

A simple Tic-Tac-Toe game built using HTML, CSS, and JavaScript.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Game Logic](#game-logic)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- Classic 3x3 grid Tic-Tac-Toe game.
- Two-player mode where players take turns.
- Displays the winner or a draw when the game ends.
- Option to restart the game without refreshing the page.
- Simple and intuitive UI design.

## Demo
You can play the game online [here](#).

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/tictactoe.git
    ```
2. Navigate to the project directory:
    ```bash
    cd tictactoe
    ```
3. Open the `index.html` file in your web browser to play the game.

## Usage
- Player 1 (X) and Player 2 (O) take turns clicking on the grid to place their mark.
- The first player to align three marks in a row, column, or diagonal wins the game.
- If all nine squares are filled without a winner, the game ends in a draw.
- Click the "Restart" button to start a new game.

## Game Logic
The game board is a 3x3 grid represented by an array. The game checks after each turn to see if there is a winner or if the game is a draw. The following conditions are checked:
- Three in a row horizontally.
- Three in a row vertically.
- Three in a row diagonally.

## Technologies Used
- **HTML5**: Markup language used for structuring the content.
- **CSS3**: Used for styling the game interface.
- **JavaScript**: Adds interactivity to the game, including game logic and user interaction handling.

## Contributing
Contributions are welcome! If you have any improvements or new features to suggest, feel free to open an issue or submit a pull request.

