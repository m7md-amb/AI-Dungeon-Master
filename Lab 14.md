# Lab 14 – AI Dungeon Master System

## Use Case Diagram

mermaid
flowchart TD
    Player -->|Interact with NPC| System
    Player -->|Explore Dungeon| System
    Player -->|Start Session| System
    GameMaster -->|Track Quest Progress| System
    GameMaster -->|Resolve Combat| System
    DiceRoller -->|Resolve Combat| System
    RulesDB -->|Retrieve Lore| System
    RulesDB -->|Look Up Rules| System


## Completed Use Case: Start Session

Actors: Player, Game Master  
Description:  
The Start Session feature is implemented in `start_session.py`.  
The player enters their name and the AI Dungeon Master  
initializes the game session with a welcome message.