# The Colony – Text-Based Horror Survival RPG

The Colony is a text-based horror survival RPG written in Java.  
You explore a hostile facility room by room, fight monsters, manage your inventory, and solve puzzles using text commands.

## Tech Stack

- Java
- JSON for storing game data (rooms, monsters, items)
- Console-based UI

## How to Run

1. Clone the repository:
   ```bash
   git clone <this-repo-url>
   cd the-colony
2. Open the project in your IDE (IntelliJ IDEA, VS Code with Java, etc.).
3. Build the project.
4. Run the Main class (or the class that contains public static void main(String[] args)).

## Gameplay

### Movement

Use the following commands to move between rooms:

- N – move north  
- S – move south  
- E – move east  
- W – move west  

The game tracks whether you have visited a room before.

### Core Commands

- Look – explore the current room  
- I – view your inventory  
- Stats – view your character’s statistics  
- Commands – view all available commands  
- Restart – restart the game  
- Exit – exit the game  

### Monsters & Combat

- Examine Monster – examine monsters in the current room  
- When you encounter a monster, you can choose to attack or ignore it.  
- Combat is turn-based: you and the monster take turns acting.  
- Attack – engage the monster in combat  
- Flee – attempt to escape from combat  

Notes:

- Choosing to ignore a monster can prevent it from respawning in some scenarios.

### Inventory Management

- Pickup {item} – pick up an item from the room  
- Explore – inspect the room for interactive objects and items  
- Drop – drop an item from your inventory  
- Equip / Un-equip – manage equipment  
- Consume – use consumable items (healing, buffs, etc.)

Use your inventory strategically to survive fights and solve encounters.

### Puzzles

- Solve – attempt to solve a puzzle in the current room.  

Some rooms contain unique puzzles that must be solved in order to progress.

### Default Map
 ____________________
|     | 19  | 18    |
|_____|_____|_______|______________
|  21 |  20 | 14/15 |  4  |  5    |
|_____|_____|_______|_____|_______|
|      | 15  | 12   |   10  |  11 |
|______|_____|______|_______|_____|
|  22  |     |   9  |     |
|------|_____|______|_____|
|  25  |   8  |    7  |  8  |
|______|______|_______|_____|
       |   8  |    6  |  8  |
       |______|_______|_____|
       |   8  |    5  |  8  |
       |______|_______|_____|
       |   8  |    4  |  8  |
       |______|_______|_____|
       |   8  |    3  | 8   |
       |______|_______|_____|
       |   8  |  1/2  |  8  |
       |______|_______|_____|

## Contributing

This project was originally developed as a team project for a software development course.  
I contributed across multiple parts of the codebase, including room exploration, combat flow, inventory interactions, and general game logic.

If you would like to contribute to the development of this game, feel free to:

- Open issues for bugs or feature ideas  
- Submit pull requests with improvements or new content  

Enjoy the game!
