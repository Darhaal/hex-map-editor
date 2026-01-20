# Hex Map Editor

**Hex Map Editor** is a web-based hexagonal map editor designed for game world prototyping, simulations, and worldbuilding.  
It allows you to create, edit, and export structured hex maps with terrain, elevation, hydrology, and infrastructure layers.

The project is implemented using **vanilla JavaScript** and **HTML5 Canvas**, without external frameworks.

---

## Features

- Hexagonal grid map system
- Multiple map visualization modes:
  - Landscape (biomes)
  - Soils
  - Hydrology
  - Elevation
- Infrastructure layers:
  - Roads (asphalt, dirt, trail)
  - Settlements
- Brush-based editing with adjustable radius
- Chain drawing for roads and rivers
- Camera controls (pan & zoom)
- Real-time legend and HUD
- Export and import maps as JSON
- Bilingual interface (EN / RU)
- Single-file, dependency-free implementation

---

## Controls

- **W / A / S / D** — move camera  
- **Mouse Wheel** — zoom  
- **Left Mouse Button** — paint / interact  
- **Drag** — continuous painting or camera movement  

---

## Map Structure

Each hex cell stores structured data, including:

- Coordinates (q, r)
- Elevation (meters)
- Soil type
- Biome type
- Hydrological data (water type, flow direction, speed)
- Infrastructure (roads, settlement)
- Administrative notes

Maps are exported in a clean, readable **JSON** format suitable for further processing in game engines or generators.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hex-map-editor.git
