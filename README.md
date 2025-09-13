# ♟️ Python Chess Game with AI

A simple yet powerful **Chess Game implemented in Python with Pygame**.  
It features a **basic AI opponent** that calculates optimal moves by looking several moves ahead using the **Negamax algorithm with Alpha-Beta pruning**.  

## 🎥 Demo
*Untitled video – Made with Clipchamp*  

---

## 🌟 Introduction
This project is a fully functional chess game with a **graphical user interface**.  
You can either:
- Play against another human player.
- Challenge the **AI opponent**, which evaluates positions and selects moves strategically.

---

## ✨ Features
- 🎨 **Graphical User Interface (GUI)**  
  Built with **Pygame**, offering an interactive and user-friendly chessboard.

- 👥 **Two-player Mode**  
  Play **human vs. human** on the same device.

- 🤖 **AI Opponent**  
  AI uses **Negamax + Alpha-Beta pruning** to calculate moves up to configurable **DEPTH** levels.

- ♟️ **Advanced Chess Rules**  
  - Checkmate & stalemate detection  
  - Legal move validation  
  - **Pawn promotion**  
  - **En passant**  
  - **Castling**

- 🔄 **Undo & Reset**  
  - Press **Z** to undo last move  
  - Press **R** to reset the board  

- 🎨 **Custom Boards & Sounds**  
  Play on **different board colors** with immersive **move & capture sounds**.  

---

## ♟️ Chess Mechanics

### En Passant
En passant allows a pawn to capture an opponent’s pawn that moved **two squares forward**.  
The capturing pawn moves to the square immediately behind the captured pawn.

### Pawn Promotion
When a pawn reaches the **eighth rank**, it can be promoted to **Queen, Rook, Bishop, or Knight**.  

---

## 🕹️ How to Play

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/chess-bot.git
   cd chess

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
  
  (Or install manually if missing: pip install pygame)

3. **Run the game**
   ```bash
   python main.py

---

##  🎮 Controls

- 🖱️ Select a piece by clicking it (highlight shows possible moves).

- 🖱️ Move a piece by clicking on a highlighted square.

- ⏪ Undo last move → Press Z

- 🔄 Reset the board → Press R

(Tip: If AI is thinking, you can click on its piece to preview possible moves.)

---

## ⚙️ AI & Settings
**Human vs Human**

**In main.py:**
  ```bash
    SET_WHITE_AS_BOT = False
    SET_BLACK_AS_BOT = False
  ```
**Human vs AI**
  ```bash
    SET_WHITE_AS_BOT = False
    SET_BLACK_AS_BOT = False
  ```
**Flip Board**

In engine.py:
  ```bash
    self.playerWantsToPlayAsBlack = False
  ```
**AI Depth**

In chessAi.py:
  ```bash
    DEPTH = 3
  ```
**⚡ Higher depth = stronger AI (but slower). Recommended 3–4 for best balance.**

---

## 🖥️ Using Visual Studio Code

1. **Open VS Code → File > Open Folder → Select repo folder.**

2. **Open terminal → Run:**
   ```bash
   python main.py

---

## 🙏 Acknowledgments

- Thanks to the Pygame library for providing a simple and powerful way to build GUIs in Python.

---

## 🤝 Contributions

This project is open to contributions!
If you’d like to report issues, suggest improvements, or add new features, feel free to open a PR or issue.

