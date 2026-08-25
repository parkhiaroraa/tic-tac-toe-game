# Tic-Tac-Toe Game in C++

A colorful, cross-platform 2-player Console-based Tic-Tac-Toe game written in C++ using Object-Oriented Programming (OOP) principles.

## 🚀 Try It Live (Run in Browser)
Click the badge below to play and test the game directly in your browser:

[![Run on OnlineGDB](https://img.shields.io/badge/Run_Code-Online-brightgreen?style=for-the-badge&logo=cplusplus)](https://onlinegdb.com/0Zt2MNHFT)

---

## 🛠️ Features
- **2-Player Mode:** Customizable player names with assigned symbols (`X` and `O`).
- **Terminal ANSI Colors:** Colored grid and messages (Red, Blue, Green, Yellow, Cyan) for an enhanced visual experience.
- **Cross-Platform Input Handling:** Supports both Windows (`conio.h`) and Linux/macOS (`termios.h` / `unistd.h`) environments without extra dependencies.
- **Dynamic Board & Win Detection:** Real-time updates with win detection across rows, columns, and diagonals, plus draw handling.
- **Interactive Restart:** Option to replay immediately with saved player names.

---

## 💻 How to Run Locally

```bash
# Clone the repository
git clone [https://github.com/YOUR-USERNAME/cpp-tictactoe-game.git](https://github.com/YOUR-USERNAME/cpp-tictactoe-game.git)

# Navigate into directory
cd cpp-tictactoe-game

# Compile with g++
g++ main.cpp -o tictactoe

# Run application
./tictactoe
