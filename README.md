# FA24-ValentineC

# FPS VR Target Shooter Game

## Project Overview
This is a First-Person Shooter (FPS) VR game developed in Unreal Engine 5. The main objective is to destroy all targets in each level to progress. Once all targets in a level are destroyed, the game either moves to the next level or returns to the main menu if the final level is completed. The game incorporates VR-specific mechanics, including teleportation, interactable objects, and a pistol with dynamic ammo tracking and reloading.

## Features

### Core Gameplay
- **Limited Ammo System**: Players have a limited ammo count displayed on a spatial UI attached to their pistol. Ammo can be replenished via a reload function triggered by a dedicated button. Shooting is disabled when ammo reaches 0.
- **Delayed Reloading**: A realistic reload mechanic with a time delay and audio feedback ensures strategic gameplay.
- **Health System**: Players can take damage from environmental hazards (if applicable) and restore health by picking up health packs, up to a maximum of 100 HP.
- **Target System**: 
  - Each target has a health value and reacts dynamically to hits:
    - First hit changes the target’s color.
    - Second hit destroys the target.
  - A counter tracks the number of targets destroyed.

### Level Progression
- **Dynamic Unlocking**: Destroying at least 1 target unlocks previously restricted teleport areas. After 3 targets, additional features unlock.
- **Win Condition**: After all targets are destroyed:
  - In non-final levels, the game proceeds to the next level.
  - In the final level, the game displays a **You Win!** message and returns to the main menu.

## How to Play
1. **Movement (VR)**:
   - Use VR controller’s teleportation mechanics to navigate the environment.
2. **Shooting**:
   - Use the trigger button to shoot targets.
   - Monitor the ammo count displayed above your pistol.
3. **Reloading Ammo**:
   - Press the reload button to replenish ammo. A delay occurs before reloading is complete.
4. **Target Interaction**:
   - Aim at targets and fire. Targets require two hits to be destroyed.
5. **Level Navigation**:
   - Clear all targets in a level to progress to the next or return to the main menu.

## Game Flow
1. **Main Menu**:
   - Select **Start Game** to begin.
2. **Level 1**:
   - Destroy all targets to unlock the no-teleport area and proceed to the next level.
3. **Level 2**:
   - Destroy all targets to win the game. A **You Win!** message is displayed, and the main menu is loaded.

## Technical Implementation
- **Pistol Blueprint**:
  - Integrated spatial UI to track ammo.
  - Delayed reload functionality with audio feedback.
- **Target Blueprint**:
  - Tracks health values and responds dynamically to hits.
  - Sends destruction events to the Level Blueprint.
- **Level Blueprint**:
  - Tracks destroyed targets.
  - Unlocks no-teleport zones dynamically.
  - Manages level progression and win conditions.

## Submission Details
- This game was developed as part of **HW2** in Unreal Engine 5.
- All required features, including VR-specific mechanics, target destruction, and level transitions, have been implemented and demonstrated.
