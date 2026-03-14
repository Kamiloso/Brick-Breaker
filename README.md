# Brick Breaker
 A university project in C++ made by Kamiloso, Peccator and Julian with SFML library.
 It is the Arkanoid-like game, where you have to clear levels with a ball and the paddle.

| ![Game screenshot](https://raw.githubusercontent.com/Kamiloso/Kamiloso/main/brickbreaker1.png) |
| ---------------------------------------------------------------------------------------------- |

## Build Instructions

1. Download the project from
   https://github.com/Kamiloso/BrickBreaker/releases

2. Open `BrickBreaker.sln` in **Visual Studio 2022**.

3. Use the following configuration:

   * **Configuration:** Release
   * **Platform:** x86 (32-bit)
   * **C++ standard:** C++14
   * **Graphics library:** SFML 2.6.2

4. Build the project.

5. Run `A-BuildFinalize.bat` from the project root.
   The script copies required assets to `./Release` and removes unnecessary files.

The final game build will appear in the `./Release` directory.

> ⚠️ Note:  
> Running the game creates `GameData/progress.bin`. Remove it after testing if a clean state is needed.
