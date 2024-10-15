# **2048 Game – Python & Tkinter Implementation**

A modern, interactive version of the **2048 puzzle game**, built with **Python** and **Tkinter**. This project demonstrates the use of data structures and algorithms to create smooth gameplay with visually appealing graphics.

## 🛠**Features**  
- **Graphical Interface**: Created using **Tkinter** for dynamic and responsive gameplay.  
- **Efficient Game Logic**:  
  - **Matrices** manage the game grid and handle tile movements and merging operations.  
  - **Dictionaries** store tile attributes like colors and styles, enabling fast lookups and game state management.  
- **Algorithms and Techniques Used**:  
  - **Matrix operations**: Transpose, reverse, and cover-up for movement handling.
  - **Recursion**: Used for merging tiles repeatedly until no more moves are possible.  
  - **State management**: Tracks win/loss conditions and maintains history for undo functionality.  
- **Random Tile Generation**: Ensures unpredictability for engaging gameplay.  
- **Undo Feature**: Allows users to backtrack steps for a better experience.

## **How to Play**  
- Use the **arrow keys** to move tiles up, down, left, or right.  
- The goal is to merge tiles and create a tile with the number **2048**.  
- If no valid moves remain, the game is over.  

## **Getting Started**  

### **Prerequisites**  
- Python 3.x installed on your machine.

### **Installation**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/2048-game.git
   cd 2048-game
   ```
2. Run the game:  
   ```bash
   python game.py
   ```

## **Project Structure**  
```
2048-game/
│
├── game.py            # Main Tkinter interface and event handling
├── logic.py           # Core game logic and algorithms
├── constants.py       # Configuration values (colors, keys, fonts, etc.)
└── README.md          # Project documentation
```

## **Lessons Learned**  
- Practical implementation of **data structures** (matrices, dictionaries) in real-world applications.  
- Use of **recursive algorithms** for efficient problem-solving.  
- Hands-on experience with **GUI development** using Tkinter.
