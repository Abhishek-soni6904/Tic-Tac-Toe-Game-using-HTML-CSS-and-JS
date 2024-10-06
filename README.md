# Tic-Tac-Toe-Game-using-HTML-CSS-and-JS

This is a simple implementation of the classic **Tic Tac Toe** game using HTML, CSS, and JavaScript. The game allows two players to alternate between "X" and "O", and features win/draw detection, a reset option, and audio-visual feedback.

## Features

- **Responsive Design:** The layout adjusts to different screen sizes.
- **Turn Display and Win Announcement:** The game displays the current turn and announces the winner or draw via both text and speech synthesis.
- **Sound Effects:** An invalid move triggers an audio alert.
- **Reset Button:** A reset button allows users to restart the game at any time.

## How to Play

1. Open the game in a browser.
2. Players take turns clicking on the empty squares to place their mark ("X" or "O").
3. The game checks for a win after each move. If a player completes a row, column, or diagonal, they win.
4. If all squares are filled and no player has won, the game results in a draw.
5. Click the **Reset** button to start a new game.

## Files

### 1. `index.html`
This file contains the structure of the game, including the game board, turn indicator, and reset button.

### 2. `style.css`
This file styles the game layout with:
- **Responsive grid layout** for the game board.
- Hover effects for the game boxes.
- A reset button with hover transitions.
- A visually appealing color scheme using gradients and shadows.

### 3. `script.js`
This file contains the game logic:
- **Player Turns:** Alternates between "X" and "O".
- **Win/Draw Detection:** Uses predefined win conditions to check the board after each move.
- **Speech Synthesis:** Announces the current player's turn and the winner/draw result.
- **Reset Functionality:** Resets the game state and clears the board when the reset button is clicked.

## Technologies Used

- **HTML5**: Structure and layout of the game.
- **CSS3**: Styling, grid layout, responsive design, and animations.
- **JavaScript**: Game logic, event handling, win detection, and sound/speech interactions.
- **Google Fonts**: Custom font (`Play`) for a modern look.
- **Speech Synthesis API**: For announcing turns and game results.

## How to Run

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Enjoy the game!

## Screenshots

Here are some screenshots of the game in action:

1. **Game Start**
   ![Game Start Screenshot](path_to_screenshot)

2. **Winning Scenario**
   ![Winning Scenario Screenshot](path_to_screenshot)

## Credits

- **Font**: [Google Fonts - Play](https://fonts.google.com/specimen/Play)
- **Sound Effects**: Custom sound for invalid moves.
