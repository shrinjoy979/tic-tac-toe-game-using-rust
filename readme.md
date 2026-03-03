# Tic Tac Toe Game (Rust CLI)

A simple Command Line Tic-Tac-Toe game built using Rust.  
Play directly in your terminal with turn-based gameplay and win/draw detection.

---

## Features

- Two-player mode (Player X vs Player O)
- Interactive CLI input
- Win detection (rows, columns, diagonals)
- Draw detection
- Input validation
- Clean modular Rust structure

---

## Built With

- Rust
- Standard Library (No external crates)

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/tic-tac-toe-game-using-rust.git
cd tic-tac-toe-game-using-rust
```

### 2. Run the project

```bash
cargo run
```

---

## How to Play

- The board is displayed as a 3x3 grid.
- Players take turns entering a number (1–9).
- Player X starts first.
- First player to align 3 marks horizontally, vertically, or diagonally wins.
- If all cells are filled and no one wins, the game ends in a draw.

### Board Layout Reference

```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
```

---

## 📂 Project Structure

```
tic-tac-toe-game-using-rust/
│
├── src/
│   ├── main.rs
│   └── game.rs
│
├── Cargo.toml
└── README.md
```

---

## Concepts Used

- Ownership and Borrowing
- Structs and Methods
- Enums and Pattern Matching
- Game Loop Logic
- CLI Input Handling

---

## Future Improvements

- Add AI using Minimax algorithm
- Improve CLI board formatting
- Add unit tests
- Add replay option
- Multiplayer over network

---

## 🤝 Contributing

Pull requests are welcome.  
Feel free to fork and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.
