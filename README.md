# Minecraft in Python 

This project is a Minecraft-like game created in Python using the Ursina game engine. It allows players to explore a procedurally generated world, place and remove blocks, and navigate using a first-person controller. The game also features a variety of block types with different textures.


## Features

```
First-Person Controller:
 Navigate the game world using the mouse and keyboard, with customizable mouse sensitivity.

Procedural Generation:
The world is procedurally generated using Perlin Noise, with different block types like grass, dirt, stone, bedrock, water, and ice.

Block Interaction:
Players can place and remove blocks by interacting with the environment, choosing from different block types using the keyboard.

Custom Textures:
 The game includes custom textures for blocks, which are loaded from the assets/textures directory.

Simple 3D Models:
The blocks in the game are based on simple 3D models, loaded from the assets/models directory.
```

## Installation
Clone the Repository:

```
git clone https://github.com/your-username/minecraft-python.git
cd minecraft-python
```
Install Dependencies: Ensure you have Python installed, and then install the required packages using pip:

```
pip install ursina perlin-noise
```

## Run the Game:
```
python main.py
```
## How to Play

```
Move: Use W, A, S, D to move around.

Jump: Press Spacebar.

Place Block: Left-click to place a block.

Remove Block: Right-click to remove a block.

Change Block Type: Use number keys (1, 2, 3, etc.) to switch between different block types.
```

##Block Types
```
Grass: Basic ground block.

Dirt: Earthy block, typically found below grass.

Stone: Stronger material, used for building.

Bedrock: The unbreakable base layer.

and more ...
```

## Assets

Models: 3D models for blocks are stored in the assets/models directory.

Textures: Block textures are stored in the assets/textures directory.


## Customization
You can customize the game by adding new block types, textures, and models. Simply place your custom textures and models in the respective directories and update the block_textures dictionary in main.py to include your new assets.

## Future Enhancements

Expand the world size and add more biomes.

Implement day-night cycles and weather effects.

Add crafting and resource management.


## This project uses the following libraries:

```
Ursina Engine: For the game engine and first-person controls.

PerlinNoise: For procedural world generation.

Custom Textures & Models: Various textures and models are used for the blocks.

Feel free to contribute or fork the repository to create your own version of the game!
```
## Screenshots

![minecraft_1](https://github.com/user-attachments/assets/7781ae56-bfad-45b0-87b5-a66ca669018c)

![minecraft_5](https://github.com/user-attachments/assets/cb91d5d0-2c16-4961-a65c-cc3a86e68d2b)

![minecraft_3](https://github.com/user-attachments/assets/9904a34c-2ecf-4522-b128-7ab6a83c6fea)

![minecraft_2](https://github.com/user-attachments/assets/fdb65807-66ff-44ab-82e4-250ee078fe96)
