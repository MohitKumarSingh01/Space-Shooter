# Space-Shooter
Here’s a sample `README.md` file for your **OpenGL Space Shooter Game** project with clickable menu (like the one in your screenshot):
![image](https://github.com/user-attachments/assets/804ac8f3-1b93-40d1-a683-ff9b734fcf20)
![image](https://github.com/user-attachments/assets/3a502e91-894c-4ec0-88b9-d7e6052a1f01)

```markdown
# 🚀 Space Shooter Game

A simple 2D space shooter game developed using **OpenGL** and **FreeGLUT**. The game features a main menu with "Start Game", "Instructions", and "Quit" options. Players can engage in a two-player space battle experience.

## 🧾 Features

- 🎮 Main Menu Interface with mouse-controlled buttons
- 👾 Two-player space shooting game
- 💥 Bullet firing mechanics
- 🔄 Game Over logic
- 📜 Instructions screen
- 🖱️ Mouse and keyboard input handling

## 📸 Screenshots

![Main Menu](screenshots/main_menu.png)

## 🛠️ Technologies Used

- C++
- OpenGL
- FreeGLUT (GL Utility Toolkit)

## 🔧 Installation

### 1. Requirements

- C++ compiler (e.g., `g++`)
- FreeGLUT and OpenGL libraries installed

### 2. Clone Repository

```bash
git clone https://github.com/your-username/space-shooter-opengl.git
cd space-shooter-opengl
```

### 3. Compile the Code (Windows with MinGW)

```bash
g++ main.cpp -o space_shooter -lfreeglut -lopengl32 -lglu32
```

### 4. Run the Game

```bash
./space_shooter
```

## 🎮 Controls

| Action             | Key/Button         |
|--------------------|--------------------|
| Player 1 Move      | Arrow Keys         |
| Player 1 Fire      | Right Ctrl         |
| Player 2 Move      | W A S D            |
| Player 2 Fire      | Spacebar           |
| Menu Selection     | Mouse Left Click   |

## 📋 Instructions

1. Run the game.
2. Click "Start Game" to begin.
3. Use the controls above to shoot and dodge bullets.
4. The first player to hit the other wins.
5. Click "Instructions" to see this guide.
6. Click "Quit" to exit the game.

## 📁 Project Structure

```
space-shooter/
│
├── main.cpp            # Main game logic
├── README.md           # This file
├── screenshots/        # Folder for screenshots (optional)
│   └── main_menu.png
```

## 🙏 Acknowledgements

- GLUT and OpenGL for graphics rendering
- Community tutorials and guides
