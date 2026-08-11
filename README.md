# Arena Warrior

Arena Shooter is a single-player FPS game developed in **Unity** using **C#**. The objective is simple: survive as long as possible, eliminate enemies, and achieve the highest score before your health reaches zero.

## Source code will be added in the near future ##

## Features

* First-person player controller
* Multiple weapons:
  * Rifle
  * Knife

* Shooting and melee combat
* Reloading system with magazine management
* Weapon inspection animations
* Health and score UI
* Main menu with:

  * Start Game
  * Options (audio settings)
  * Quit
* Continuous enemy spawning system

## Enemy AI

Enemies use Unity's **NavMesh** for pathfinding and follow a state-based behavior system consisting of three states:

* **Roaming** – enemies patrol the arena randomly.
* **Chasing** – enemies detect and pursue the player when within range.
* **Attacking** – enemies attack once they are close enough to the player.

After an enemy is defeated, it is removed from the scene and a new enemy is spawned, creating a continuous gameplay loop.

## Gameplay

The player starts inside an arena where enemies continuously spawn. Every defeated enemy increases the player's score. The game ends when the player's health reaches zero.

The goal is to survive as long as possible while achieving the highest score.

## Technologies

* Unity
* C#
* Unity NavMesh
* Unity Animation System
* Unity UI

## Programming Concepts

* Object-Oriented Programming (OOP)
* State-based AI behavior
* Event-driven gameplay systems
* Modular gameplay architecture
* Game state management

## Future Improvements

* Additional enemy types
* Power-ups and pickups
* Wave-based progression
* Save system and high scores
* Sound effects and background music
* Difficulty scaling
* More weapons and maps

## Screenshots

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/eb045224-af73-49fd-a393-568c10dee5b7" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0de5aeac-fd0a-460b-a7dd-540bad5c37ae" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d6150032-5240-4467-8cae-7af154977a8c" />



## Author

Srđan Perišić
