# Bubble Pop
A simple [Godot](https://godotengine.org/) project to learn about 2D sprite movement and mouse clicking.

## Instructions
The project instructions begin here - [Bubble Pop: 1. Project Setup](https://gitlab.com/kirkja-leikjahonnunar/knowhow/-/tree/main/Tinker/Drills/BubblePop/1.%20Project%20Setup%20).


### Important Nodes, Properties, and Functions.

#### `Node`
- Parent Node: `get_parent()`
- Spawn: `PackedScene.instantiate()`
- De-spawn: `queue_free()`
- Player mouse input.

#### `Node2D` / `Area2D`
- 2D Transformation properties:
  - `Node2D.position.x`
  - `Node2D.position.y`
  - `Node2D.rotation`
  - `Node2D.scale.x`
  - `Node2D.scale.y`

#### `CollisionShape2D`
- `Inspector` > `CollisionShape2D` >`Shape`

#### `Sprite2D`
- `Inspector` > `Sprite2D` > `Texture`

#### `Timer`
- Signal: `time_out()`

### GDScript Topics
- Variables.
- Functions.
- Event Signals.
