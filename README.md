# PRO100 Dungeon TBRPG

A turn-based role-playing game built in Unity featuring dungeon exploration, tactical combat, and character progression.

## Group Members
- **Ethan Townsend**
- **Gunnar Huscroft**
- **Jacob Brincefield**
- **Victor Keeler**

## Project Overview
This project is a **Turn-Based Role-Playing Game (TBRPG)** set in a dungeon environment. Players explore procedurally generated dungeons, engage in strategic turn-based combat with enemies, manage their inventory, and progress their character through multiple game areas.

## Key Features
- **Turn-Based Combat System**: Strategic battles with enemies using a comprehensive battle system
- **Player Progression**: Level up your character, gain experience, and improve stats
- **Dungeon Generation**: Explore procedurally generated dungeon layouts
- **Inventory Management**: Collect and manage items throughout your adventure  
- **Multiple Game Areas**: Navigate between different scenes including Courtyard, Dungeon, and House
- **Battle HUD**: Intuitive user interface for combat encounters
- **Scene Management**: Seamless transitions between different game areas

## How to Run the Project

### Prerequisites
- **Unity 2022.3 LTS** or newer
- **Git** for version control

### Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/snxethan/PRO100-DUNGEON_TBRPG.git
   ```

2. **Open in Unity**:
   - Launch Unity Hub
   - Click "Open" and navigate to the cloned project folder
   - Select the project and wait for Unity to import all assets

3. **Check Dependencies**:
   - Unity should automatically import required packages
   - Verify that DOTween plugin is properly imported in `Assets/Plugins/Demigiant/DOTween`

4. **Run the Game**:
   - Open any scene from `Assets/Scenes/` (start with `Courtyard.unity` for the main experience)
   - Press the Play button in Unity Editor
   - Use WASD keys to move your character
   - Approach enemies to engage in turn-based combat

## Game Controls
- **WASD**: Move player character
- **Mouse**: Navigate menus and battle interface
- **Enter/Space**: Confirm selections in battle

## Project Structure
```
Assets/
├── Scripts/Gameplay/
│   ├── Player/           # Player controller and mechanics
│   ├── Battle/           # Turn-based combat system
│   ├── DungeonGen/       # Procedural dungeon generation
│   ├── Inventory/        # Item and inventory management
│   └── Core/             # Essential game systems
├── Scenes/               # Game scenes and levels
├── Prefabs/              # Reusable game objects
└── Art/                  # Game assets and visuals
```

## Contributing
We welcome contributions to improve the game! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is developed as a class assignment. Please contact the group members for usage permissions.


