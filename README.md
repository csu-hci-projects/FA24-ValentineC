# FA24-ValentineC

Project Overview
This is a First-Person Shooter (FPS) game developed in Unreal Engine. The objective of the game is to destroy all targets in each level. Once all targets are destroyed, the game will either progress to the next level or return to the main menu if the final level is completed.

Game Features
Limited Ammo: The player has a limited ammo count, which can be replenished by picking up ammo pickups scattered throughout each level.
Health System: The player has a health bar that decreases upon taking damage. Health pickups are available to restore the player's health but cannot exceed the maximum value of 100.
Target System: Targets are placed throughout each level and have their own health. The player must destroy all targets in a level to progress.
Level Progression: Once all targets in a level are destroyed:
If the current level is not the final level, the game will load the next level.
If the current level is the final level, the game will load the main menu.
How to Play
Movement: Use W, A, S, and D keys to move around.
Shooting: Use the left mouse button to shoot.
Reloading Ammo: Pick up ammo boxes scattered throughout the level to replenish ammo.
Healing: Pick up health packs to restore health. Health cannot exceed 100.
Game Flow
Start the game from the main menu by selecting Start Game.
Progress through levels by destroying all targets in each level.
When all targets are destroyed:
If you are in Level 1, the game will progress to Level 2.
If you are in Level 2, the game will return to the main menu.
Requirements
Unreal Engine: This project is developed in Unreal Engine. Make sure you have Unreal Engine installed on your computer to open and run the project.
Supported Platforms: This project is configured to work on Windows. It may work on other platforms, but additional setup may be required.
Project Setup Instructions
Open the project in Unreal Engine.
Make sure the required assets are loaded (e.g., target, ammo, health pickup assets).
In Project Settings:
Set the Game Mode to the custom Game Mode that handles level transitions and target tracking.
Play the game from the main menu to start Level 1.
