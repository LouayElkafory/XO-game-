# 🎮 XO Game - Assembly Language Project

## 📋 Project Overview
A complete Tic-Tac-Toe (XO) game implemented in x86 Assembly Language using EMU8086 emulator. Two players take turns placing X and O on a 3x3 grid, with automatic win detection and game management.

## ✨ Features
- **Two-player gameplay** (X vs O)
- **Smart win detection** - checks all 8 winning combinations
- **Tie game recognition** - detects when board is full
- **Input validation** - prevents invalid moves
- **Clean text interface** - easy to use and understand

## 🎯 How to Play
1. Run the program in EMU8086
2. Players alternate turns entering numbers 1-9
3. Select empty cells to place your symbol (X or O)
4. First player to get 3 in a row (any direction) wins!
5. Game ends when someone wins or all cells are filled

## 🏗️ Project Structure
The project is divided into three main modules:

### 1. Board Management
- Manages game board and player data
- Handles player switching (X ↔ O)
- Updates board after each move

### 2. Win Detection  
- Checks all possible winning combinations
- Detects horizontal, vertical, and diagonal wins
- Identifies tie games

### 3. Main Controller
- Manages game flow and user interface
- Handles player input and validation
- Displays game messages and results

## 🔧 Technical Details
- **Language**: x86 Assembly
- **Platform**: EMU8086 Emulator
- **Architecture**: Modular design with separate components
- **Features**: Full error handling and input validation

## 🚀 Getting Started
1. Install EMU8086 emulator
2. Open the main.asm file
3. Compile and run (F5)
4. Follow on-screen instructions to play

## 👥 Team
- **Board Manager**: [louay mohamed ]
- **Win Checker**: [ sohila ehab ] 
- **Main Controller**: [lama diaa]

---

*Experience classic gaming at the lowest level of programming!*
