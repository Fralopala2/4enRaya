# 🔴🟡 4 en Raya (Connect Four)

[![Game](https://img.shields.io/badge/Game-Connect%20Four-orange?style=for-the-badge&logo=gamepad)](https://github.com/Fralopala2/4enRaya)
[![Educational](https://img.shields.io/badge/Educational-Class%20Project-blue?style=flat&logo=graduation-cap)](https://github.com/Fralopala2/4enRaya)
[![Status](https://img.shields.io/badge/Status-Completed-green?style=flat&logo=check-circle)](https://github.com/Fralopala2/4enRaya)

> **Classic Connect Four game** implementation for educational purposes

## 🎮 About the Game

Connect Four (4 en Raya) is a classic strategy game where players take turns dropping colored discs into a vertical grid. The objective is to be the first to form a line of four of your own discs horizontally, vertically, or diagonally.

## ✨ Features

- 🎯 **Classic Gameplay** - Traditional Connect Four rules
- 👥 **Two Player Mode** - Play against a friend
- 🎨 **Visual Interface** - Clear game board representation
- 🏆 **Win Detection** - Automatic victory condition checking
- 🔄 **Game Reset** - Start new games easily
- 📚 **Educational Code** - Well-documented for learning

## 🚀 Quick Start

### Prerequisites
- [Add your programming language/runtime]
- [Add any dependencies]

### Installation & Play

1. **Clone the repository**
   ```bash
   git clone https://github.com/Fralopala2/4enRaya.git
   cd 4enRaya
   ```

2. **Run the game**
   ```bash
   # Add your run command here
   # Example: python main.py
   # Example: java ConnectFour
   # Example: node app.js
   ```

3. **Start playing!**
   - Player 1: Red discs (🔴)
   - Player 2: Yellow discs (🟡)

## 🎮 How to Play

1. **Choose Column** - Select where to drop your disc
2. **Take Turns** - Players alternate moves
3. **Win Condition** - Get 4 in a row (horizontal, vertical, or diagonal)
4. **Victory!** - First player to connect four wins

```
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   | 🟡|   |   |   |
|   |   | 🔴| 🟡|   |   |   |
|   | 🔴| 🟡| 🔴|   |   |   |
| 🟡| 🔴| 🟡| 🔴| 🟡|   |   |
 1   2   3   4   5   6   7
```

## 🏗️ Project Structure

```
4enRaya/
├── src/
│   ├── game.py          # Core game logic
│   ├── board.py         # Game board management
│   └── player.py        # Player class
├── tests/
│   └── test_game.py     # Unit tests
├── README.md
└── requirements.txt
```

## 🧠 Game Logic

### Core Functions
- **`drop_disc(column, player)`** - Place disc in column
- **`check_winner()`** - Detect victory conditions
- **`is_valid_move(column)`** - Validate column selection
- **`reset_game()`** - Start new game

### Win Conditions
- ✅ **Horizontal** - 4 consecutive discs in a row
- ✅ **Vertical** - 4 consecutive discs in a column  
- ✅ **Diagonal** - 4 consecutive discs diagonally

## 🎓 Educational Value

This project demonstrates:
- **Algorithm Design** - Game state management
- **Data Structures** - 2D arrays for game board
- **Logic Programming** - Win condition detection
- **User Interface** - Interactive game display
- **Object-Oriented Design** - Player and board classes

## 🔧 Customization

Easily modify game parameters:

```python
# Game configuration
ROWS = 6
COLUMNS = 7
WIN_LENGTH = 4
PLAYER_COLORS = ['🔴', '🟡']
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push branch (`git push origin feature/improvement`)
5. Open Pull Request

## 📚 Learning Resources

- [Connect Four Strategy Guide](https://en.wikipedia.org/wiki/Connect_Four)
- [Game Theory Basics](https://en.wikipedia.org/wiki/Game_theory)
- [Algorithm Implementation Tips](https://en.wikipedia.org/wiki/Connect_Four#Mathematical_solution)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>🎮 Built for learning and fun!</p>
  <p>⭐ Star this repo if you enjoyed the game!</p>
</div>
