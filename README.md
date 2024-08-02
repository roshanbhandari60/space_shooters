
# Space Shooters 

Space Shooters is a classic arcade-style shooting game where players control a spaceship and defend against waves of enemy ships. The game is built using C++ and Raylib for graphics, providing a smooth and engaging gameplay experience.

Features :
    Player Control: Move the spaceship and shoot projectiles to destroy enemies.
    Enemy Waves: Different types of enemies with unique movement patterns.
Scoring System: Earn points by destroying enemies.
Collision Detection: Detects and handles collisions between the player’s ship, enemies, and projectiles.
## Features

- Player Control: Move the spaceship and shoot projectiles to destroy enemies.
- Enemy Waves: Different types of enemies with unique movement patterns.
- Scoring System: Earn points by destroying enemies.
- Collision Detection: Detects and handles collisions between the player’s ship, enemies, and projectiles.


## Installation

1. Clone the repository

```bash
  
  git clone https://github.com/roshanbhandari60/space_shooters.git

```
2. Navigate to the project directory
```bash
cd space_shooters/src
```
3. Install Raylib by following the instructions on the Raylib website https://www.raylib.com/.
## Building the game

1. Compile the source files with the Raylib library:
```bash
    g++ -o space_shooters main.cpp player.cpp enemy.cpp projectile.cpp -lraylib -std=c++11 -ldl -lpthread -lm -lX11

```
2. Go to the game directory:
```bash 
    ./space_shooters/src/game.cpp
```
3. Press F5 or fn + F5 to run the project

## Project Structure

 - `game.cpp`: Entry point of the game.
 - `alien.cpp` : manages the alien ship .
 - `laser.cpp`: handles laser .
 - `obstacle.cpp`: creates obstacles between alienship and  spaceship
 - `main.cpp` : combines all the other classes and implements logic 




## Authors

- [@PrashantPoudel](https://www.github.com/prashantpoudel745)
- [@RoshanBhandari](https://github.com/roshanbhandari60)
- [@RiteshPokherel](https://github.com/RiteshPokharel)
  
## Feedback

If you have any feedback, feel free to reach out to one of the authors . Your feedback is valued .
