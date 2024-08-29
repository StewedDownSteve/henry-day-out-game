# henry-day-out-game
2D Game with Godot, Godot Script, Resprite

# Henry's Day Out
Welcome to "Henry's Day Out," a 2D action game developed using the Godot engine. This game features Henry, a brave cat exploring an open world filled with various enemies and challenges. The objective is to navigate through the environment, defeat enemies, and collect experience points to enhance Henry's abilities.


#### Enemy Pixel Art and Planning
![Game Enemy Art](https://github.com/StewedDownSteve/henry-day-out-game/blob/main/henry-game-art1.png)
#### Player Pixel Art and Planning
![Game Character Art](https://github.com/StewedDownSteve/henry-day-out-game/blob/main/henry-game-art2.png)

## How It's Made:

**Tech used:** Godot Engine, Godot Script (GDScript), Resprite (for pixel art)

This project was built using the Godot engine and GDScript, which is similar to Python in syntax and offers a robust environment for game development. I created the pixel art sprite sheets using Resprite, which helped bring the game's characters and environment to life.

### Key Features:
- Reusable Controllers: The game features reusable controllers for movement, physics, and enemy AI. By utilizing object-oriented programming principles and inheritance, we created base nodes for characters and enemies that can be extended and customized. This modular approach allowed us to efficiently manage game mechanics and ensure consistency across different     game elements.
- Dynamic Environment: The game environment is procedurally generated just off-screen, creating a continuous and engaging world for the player. This feature includes pixel art tiles for grass, water, and other elements, with water tiles intelligently grouping to form ponds rather than being scattered randomly.
- Advanced Enemy AI: The enemy AI is designed to seek out the player, navigate around obstacles, and adjust its behavior based on environmental factors. This includes avoiding edges of water and other obstacles, as well as interacting with other enemies in a coordinated manner.
- Structured Game Levels: We implemented a system where different game elements (e.g., hitboxes, item collectors) are managed on separate levels. This separation ensures that interactions are controlled and prevents unintended consequences, such as enemies picking up items they shouldn't.


## Optimizations
During development, we frequently revisited and refactored the game's code. Initially, we began with a rudimentary setup, but as we gained more understanding of Godot's features and best practices, we improved the code structure significantly. Key optimizations included creating dedicated controllers for gravity and movement, and refining the AI to enhance performance and behavior.

Collaboration & Version Control: This project was an ongoing collaboration with a more experienced friend, which provided invaluable insights and guidance. I gained significant experience using Git in a production environment, including branching, testing changes before committing, and managing merge conflicts. This experience enhanced my ability to work effectively in a team setting and maintain a clean and functional codebase.


## Lessons Learned:

I gained a deep understanding of game development principles, including the intricacies of physics and collision detection in Godot. I also learned valuable lessons about pixel art and animation, and how to manage complex interactions within a game environment. This project reinforced my skills in modular design, iterative improvement, and collaborative problem-solving, all of which are crucial in full-stack development and software engineering.

## Examples:
Take a look at these couple of examples that I have in my own portfolio:

**Palettable:** https://github.com/
