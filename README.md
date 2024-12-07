# FA24-ValentineC

# FPS Target Shooter Game

## Project Overview
This is a First-Person Shooter (FPS) game developed in Unreal Engine. The main objective is to destroy all targets in each level to progress. Once all targets in a level are destroyed, the game either moves to the next level or returns to the main menu if the final level is completed.

## Features
- **Limited Ammo**: Players have a limited ammo count, which can be replenished by picking up ammo pickups scattered across each level.
- **Health System**: The player has a health bar that decreases upon taking damage. Health pickups are available to restore health, up to a maximum of 100.
- **Target System**: Each level contains targets with individual health values. Destroying all targets in a level allows the player to progress.
- **Level Progression**: 
  - If all targets in a level are destroyed and it's not the final level, the game proceeds to the next level.
  - If all targets in the final level are destroyed, the game returns to the main menu.

## How to Play
1. **Movement**: Use `W`, `A`, `S`, and `D` keys to move.
2. **Shooting**: Left-click the mouse button to shoot.
3. **Reloading Ammo**: Pick up ammo boxes found throughout each level to replenish your ammo.
4. **Healing**: Pick up health packs to restore health, but health cannot exceed 100.

## Game Flow
1. Start the game from the **main menu** by selecting **Start Game**.
2. Destroy all targets in each level to progress.
3. After all targets are destroyed:
   - In Level 1, the game will load Level 2.
   - In Level 2 (the final level), the game will load the main menu, signaling the game's completion.

