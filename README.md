# The last Pilgrimage
    Name: Durlesteanu Victor-Andrei
    For all classes I have used:
        Java - temurin-21.0.8 using IntelliJ IDEA 2025.2 (Ultimate Edition)
    For the DataBase, I have used:
        SQLite version : 3.52.0
    To connect my Java classes to database I have used:
        JDBC version : 13.2

# What is it?
You are a knight that has fallen back in a cave from the evil forces. It is up to you to come back, fight your way to the nearby village and into the castle, where the enemy overlord is located, while avoiding minions and traps throughout the three levels. 

## How is it created
This project was entirely created using **Java**. I utilized **JDBC** and **SQLite** to store game data. The game architecture implements several solid design patterns, including **Singleton**, **Factory**, and **Observer**. 

### Key Features & Mechanics
* **NPCs & Combat:** The game features two types of NPCs: enemies and friendly characters. Killing monsters grants accumulated points. The player has two types of attacks. Regular one that does regular damage and *special attack* that uses stamina and does double the damage.
* **Health System:** The player starts with 100 health points. If damage is taken, health can be replenished by interacting with chests scattered throughout the maps. The player also has a stamina bar that he can use to do a *special attack*. This stamina will be replenished over time.
* **Save & Load System:** Players have the option to save their progress and load it later, or start a fresh game. Progress is automatically saved upon completing a level. If the player dies, the game loads the most recent save.
* **Custom UI Menus:** The game includes fully functional custom menus: Main Menu, Pause Menu, Settings Menu, Next-Level Menu, and Game-Over Menu.

---

## Levels
### Level One: The Cave
You awaken in a cave and must make your way back to the village just outside. This level serves as a tutorial, featuring a low number of enemies to help the player learn the mechanics.

### Level Two: The Forest
After exiting the cave, you find the villagers outside, terrified. You can choose to interact with them for lore or simply progress through the level. This area contains a fair amount of enemies to challenge the player.

### Level Three: The Castle
Upon entering the castle, you are one step closer to the enemy overlord. This final level includes a high number of enemies. Once completed, the game returns to the main menu.

---

## Controls
* **A** - Move left
* **D** - Move right
* **SPACE** - Jump
* **CTRL + A/D** - Crouch moving
* **K** - Special attack
* **J** - Default attack
* **E** - Interact

---

# How to run:
1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Configure Project Structure.
    *   Right-click the `resources` folder and mark it as **"Resources Root"**.
    *   Right-click the `src` folder and mark it as **"Sources Root"**.
4. Run the `Main` class to launch the game.
5. Enjoy!

