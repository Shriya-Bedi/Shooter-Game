# Shooter-Game

This is a basic First Person 3D shooter game developed in Unreal Engine. The game includes combat mechanics, win/lose conditions, AI implementations and a simple user interface.

## Gameplay

- Enemies will spawn at a distance and move towards the player.
- Use weapon (loaded at the beginning with the player) to shoot and defeat the enemies.
- Each enemy has a certain amount of health and will be eliminated after being hit a specific number of times.
- If you manage to defeat more than 20 enemies, the game is won.
- However, if any enemy gets too close to you, you lose.

## User Interface



## Development Process

- Step 1: Set up project repository
- Step 2: Creating the Unreal Engine project
- Step 3: Building the First-Person character
  * Attached gun to player by default
  * Implemented a third-person blueprints to position camera and control movements like walking/running
  * Implemented the Weapon logic (animations, damage values)
  * Created blueprints classes to handle player characteristics
  * Added sound effects
- Step 4: Building the AI Enemy character
  * Created Blueprints and Animations for the enemy player
  * Attached logic for receiving damage and dealing damage when player radius is breached
  * Added AI perception (Sight) for enemy to sense and move towards player
  * Implemented behaviour tree to handle logic for chasing and attacking player
- Step 5: Overall Game Logic
  * Linked the necessary components to handle damage to enemy
  * Added checks to track number of enemies killed
  * Implemented exit conditions for the game:
- Step 6: Environment Building
  * Imported Infinity Blade assets and environment (they were the nicest looking ones for free)
  * Added navigation mesh for AI paths
  * Added Game Over screen and displayed total kills in viewport
  

## References
Documentation:
- https://dev.epicgames.com/documentation/en-us/unreal-engine/understanding-the-basics-of-unreal-engine
- https://dev.epicgames.com/documentation/en-us/unreal-engine/introduction-to-blueprints-visual-scripting-in-unreal-engine
- https://dev.epicgames.com/documentation/en-us/unreal-engine/programming-with-cplusplus-in-unreal-engine
YouTube Videos:
- AI Behaviour Tree Tutorial: https://www.youtube.com/watch?v=k6Gkhg0rwC4&ab_channel=UnrealByYourself
- Kill Enemies Tutorial: https://www.youtube.com/watch?v=jXnRNLYyfxA&t=14s&ab_channel=MattAspland
- Unreal Engine 5 | Blueprint For Beginners: https://www.youtube.com/watch?v=Xw9QEMFInYU&ab_channel=SmartPoly
