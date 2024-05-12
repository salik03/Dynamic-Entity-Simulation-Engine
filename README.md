# Dynamic Entity Simulation Engine

Welcome to the official repository of Dynamic Entity Simulation Engine, a robust and interactive 2D action game framework developed using Unity. This engine provides a flexible platform for creating games with dynamic entity behaviors, intricate physics simulations, and real-time interactions.

## Features

- **Dynamic Entity Management**: Utilize a robust system for spawning, managing, and recycling entity instances (balls and bullets) dynamically.
- **Advanced 2D Physics**: Experience smooth and realistic physics interactions with custom 2D physics integration.
- **Wrapping World Mechanics**: Explore a continuous 2D world where entities wrap around the edges, creating endless gameplay possibilities.
- **Real-Time Animation Techniques**: Implement time extrapolation and interpolation for fluid and responsive animations.
- **Interactive Gameplay Elements**: Control a player entity that responds intuitively to user input and game dynamics.
- **Efficient Rendering**: Employ Unity’s latest rendering techniques to ensure optimal performance even with numerous entities.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Unity Editor (version 2022.3.4f1 or newer)
- Git (for version control)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/DynamicEntitySimulationEngine.git
   ```
2. **Open the project in Unity**:
   - Launch Visual Studio Code
   - Select Assembly-CSharp.csproj in the editor
   - Under scripts select any script

## Development

### Adding New Entities

- To add a new entity type, create a prefab and a corresponding manager script following the existing `BallManager` and `BulletManager` structure.
- Ensure all entity physics and interactions are handled through the job system for efficiency.

### Customizing Physics

- Modify the `PhysicsSettings` scriptable object to tweak global physics parameters like gravity, friction, and bounce characteristics.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
