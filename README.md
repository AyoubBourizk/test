# Chess Website

A simple, interactive chess game built with JavaScript, HTML, and CSS. Play classic chess directly in your browser, featuring piece movement, capture, castling, and turn-based play.

---

## Features

- **Interactive Chessboard:** Click pieces and valid moves are highlighted.
- **Standard Chess Rules:** Supports all chess moves, including castling and pawn promotion.
- **Turn-Based Gameplay:** Alternates between White and Black, updates turn indicators.
- **Piece Capture:** Captured pieces are removed from the board.
- **Responsive UI:** Clean, web-based interface using modern HTML/CSS.

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, etc.)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AyoubBourizk/test.git
   cd test
   ```

2. **Open the game:**
   - Double-click `index.html`  
   **or**  
   - Serve the folder with a simple HTTP server:
     ```bash
     python -m http.server
     ```
     Then visit `http://localhost:8000` in your browser.

---

## How to Play

1. **Start the Game:** The board is initialized automatically.
2. **Move Pieces:** Click a piece to highlight its possible moves, then click a target square to move.
3. **Capturing:** Move your piece onto an opponent’s piece to capture it.
4. **Castling:** Castling is enabled if neither the king nor the rook has moved, and the path is clear.
5. **Turn Indicator:** The current player's turn is displayed above the board.

---

## Project Structure

```
.
├── index.html      # Main HTML file for the chessboard
├── style.css       # Styling for the board and pieces
└── script.js       # Game logic (piece movement, rules, etc.)
```

---

## Customization

- **Board Style:** Modify `style.css` to change the appearance.
- **Game Logic:** Extend or tweak rules in `script.js` for custom chess rules or variants.

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change or add.

---

## License

This project is open source. Add a license if you wish to specify your terms.

---

## Credits

- Chess piece Unicode symbols courtesy of the Unicode Standard.
- Developed by [AyoubBourizk](https://github.com/AyoubBourizk).

---