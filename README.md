# 🐍 SFML Snake Game  
*A C++ Snake Game with Modern Graphics*  


## 🛠️ Built With  
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" width="100" title="C++">
  
  <img src="https://www.sfml-dev.org/images/logo.png" width="100" title="SFML">
  
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Cmake.svg" width="100" title="CMake">
</p>

![Snake Game Screenshot](https://via.placeholder.com/600x400/222222/FFFFFF?text=Snake+Game+Demo)  
*(Replace with actual screenshot later)*  

---

## 📝 **Project Overview**  
A classic Snake game built in **C++** using the **SFML library**, featuring:  
- 🕹️ **Keyboard-controlled** snake movement (Arrow Keys)  
- 🍎 **Food collision** detection & score tracking  
- 🚧 **Wall/self-collision** detection (Game Over)  
- 🖥️ **Smooth graphics** with SFML rendering  

**Perfect for demonstrating**:  
- Object-oriented programming (OOP)  
- Real-time input handling  
- 2D game physics  

---

## 🛠️ **Installation (macOS)**  
1. **Install SFML**:  
   ```bash
   brew install sfml

   2. Clone th repo:
   ```bash
   git clone https://github.com/your-username/snake-game-sfml.git

   3. Complie & run:
   ```bash
   g++ snake.cpp -o snake -lsfml-graphics -lsfml-window -lsfml-system
./snake

---

## 🎮 How to Play

| Key       | Action         |  
|-----------|----------------|  
| `↑`/`W`   | Move Up        |  
| `↓`/`S`   | Move Down      |  
| `←`/`A`   | Move Left      |  
| `→`/`D`   | Move Right     |  

---

## 📊 Code Structure
```bash
snake-game-sfml/  
├── snake.cpp        # Main game logic  
├── README.md        # This file  
└── CMakeLists.txt   # Build config (optional)

Key Functions:

- handleInput(): Processes keyboard events
- update(): Moves snake and checks collisions
- render(): Draws graphics using SFML

---

## 📚 Resources

SFML Documentation
GitHub Repo


