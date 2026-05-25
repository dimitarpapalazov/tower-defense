# Tower Defense

A retro-style, pixel-art Tower Defense game built with the Phaser 3 game engine.

## Description

This project is a classic Tower Defense game where players must strategically place defensive towers to prevent waves of creeps from reaching the end of the path. The game features:

- **Multiple Enemy Types**: Including standard Creeps, Armored Creeps, and Absorber Creeps.
- **Diverse Tower Arsenal**: Choose between Normal Towers, Cannon Towers, and Magical Towers to counter different enemy threats.
- **Level System**: Progress through multiple levels with increasing difficulty and unique path layouts.
- **Resource Management**: Earn coins by defeating enemies to upgrade your defenses and manage your hearts to survive the onslaught.
- **Retro Aesthetic**: High-quality pixel art and a custom VT323 font for a nostalgic arcade feel.

## Motivation

This project was developed as my **Bachelor's Thesis**. It stems from my deep love for game development and a desire to explore the intricacies of real-time strategy mechanics, pathfinding, and game state management. Creating this game allowed me to combine my academic learning with my passion for creating interactive experiences.

## Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd tower-defense
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open in browser**:
   Navigate to `http://localhost:5173` (or the port specified in your terminal) to start playing.

## Usage

- **Main Menu**: Start a new game or select a specific level.
- **Building**: Click on available slots on the map to build towers. Each tower type has a different cost and effectiveness.
- **Gameplay**:
  - Defeat enemies to earn coins.
  - Use coins to build more towers.
  - If enemies reach the end of the path, you lose hearts.
  - Clear all waves to win the level!
- **Level Creation**: Use the built-in level editor to design and test your own custom paths and wave configurations.
- **Level Selection**: Challenge different levels from the Level Select screen.

## Technologies Used

- **Game Engine**: [Phaser 3](https://phaser.io/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Language**: JavaScript (ES6+)
- **Assets**: Custom pixel art and retro sound effects.
