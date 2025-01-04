Core objects as described by ChatGPT

# Relevant Unity Entities/Objects for a 2D Platformer

## Core Components
- **GameObject**: The fundamental building block for all objects in Unity.
- **Transform**: Defines an object's position, rotation, and scale in the scene.
- **Rigidbody2D**: Enables physics-based movement and interactions for 2D objects.
- **Collider2D**: Defines the shape of an object for collision detection (e.g., BoxCollider2D, CircleCollider2D).
- **Sprite Renderer**: Renders 2D sprites in the scene.

## Input and Interaction
- **Input System**: Handles player input from keyboard, mouse, or controllers.
- **Event System**: Manages input events for UI interactions and menus.

## Physics and Movement
- **Physics Material 2D**: Controls friction and bounciness of colliders.
- **Effector2D**: Modifies physics behavior, such as one-way platforms with PlatformEffector2D.

## Level Design and Environment
- **Tilemap**: A grid-based system for creating and managing 2D environments.
- **Tilemap Collider2D**: Adds colliders to tiles for interaction with objects.
- **Sorting Layers**: Organizes rendering order for sprites (e.g., background, foreground).

## Animation
- **Animator**: Manages animation states and transitions.
- **Animation Clip**: Defines individual animations for objects (e.g., running, jumping).

## Logic and Game Management
- **ScriptableObject**: Stores reusable and shareable data (e.g., character stats, game settings).
- **Prefab**: A template for creating reusable instances of objects (e.g., enemies, platforms).
- **Audio Source**: Plays sound effects and background music.
- **UI Canvas**: Displays UI elements such as health bars, score, and menus.

## Utility
- **Camera**: Renders the game world and can be set to an orthographic view for 2D games.
- **Particle System**: Creates visual effects like explosions, dust, or sparkles.
- **Lighting (2D)**: Adds dynamic lighting and shadows to enhance visual depth.

