# Tic Tac Toe

A classic Tic Tac Toe game built with vanilla JavaScript, HTML, and CSS. Play against a friend in this clean, responsive implementation of the timeless strategy game.

## How to Play

1. The game starts with Player X's turn
2. Click any empty cell to place your mark (X or O)
3. Players alternate turns
4. First player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
5. If all 9 cells are filled with no winner, the game ends in a draw
6. Click "Restart Game" to play again

**[Play the Game](https://lgxcodes.github.io/TicTacToe/)**

## Technologies Used

- **HTML** - Semantic markup structure
- **CSS** - Styling with CSS Grid layout
- **JavaScript** - Game logic and DOM manipulation

## Features

- **Turn-based gameplay** - Alternating turns between X and O players
- **Win detection** - Automatically detects all 8 possible winning combinations (rows, columns, diagonals)
- **Draw detection** - Recognizes when the board is full with no winner
- **Game state management** - Prevents invalid moves and tracks the current game state
- **Instant restart** - Reset the game board and start a new match anytime
- **Responsive design** - Works seamlessly on desktop and mobile devices
- **Clean UI** - Simple, intuitive interface with custom typography

## Key Implementation Details

- **Event Delegation**: Efficient click handling using event listeners
- **Win Condition Algorithm**: Checks 8 possible win patterns after each move
- **State Management**: Tracks board state in a simple array structure
- **DOM Manipulation**: Real-time updates to the game board and status messages

## Project Structure

```
TicTacToe/
├── index.html      # Main HTML structure
├── index.js        # Game logic and functionality
├── styles.css      # Styling and layout
└── README.md       # Project documentation
```
