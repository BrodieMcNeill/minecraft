# Voxel Survival

A browser-playable Minecraft-inspired voxel survival prototype.

## Run
Open `index.html` in a modern browser. Internet access is required because Three.js is loaded from jsDelivr.

## Controls
- WASD: move
- Shift: sprint
- Space: jump
- Mouse: look
- Hold left click: mine
- Right click: place
- 1–9: select hotbar
- Esc: release mouse

## Architecture
The prototype keeps world data in a voxel map and separates terrain generation, rendering, player physics, interaction, and inventory logic so additional systems can be added later.
