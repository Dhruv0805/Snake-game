# Snake Game

A classic Snake game built in **C++** using the **Raylib** graphics library.

## Features
- Classic snake gameplay
- Food collection and score system
- Sound effects and graphics
- Simple and lightweight

## Requirements
- C++ compiler (GCC/MinGW or MSVC)
- Raylib library

## Project Structure
```
Snake-game-main/
├── main4.cpp
├── main4.exe
├── raylib.dll
├── README.md
└── gameTool/
    ├── Food.png
    ├── eat.mp3
    ├── Stating.mp3
    └── GameOver.mp3
```

## How to Compile
Compile `main4.cpp` with the Raylib library installed and linked.

Example (MinGW):
```bash
g++ main4.cpp -o SnakeGame -lraylib -lopengl32 -lgdi32 -lwinmm
```

## How to Run
Run `main4.exe` or the compiled executable.

## Controls
- Arrow Keys - Move the snake

## Note
> **If you download the `.exe` file, do not forget to download both `raylib.dll` and the `gameTool` folder. Without them, the executable will not work.**
>
> **The same applies when compiling the source code—you must have `raylib.dll` and the `gameTool` folder available, otherwise the game will not run correctly.**

## License
This project is for educational purposes.
