# RPG Character Builder

RPG Character Builder is an immersive Angular application designed for tabletop gamers, RPG enthusiasts, and storytellers. Create, customize, and manage unique fantasy characters and guilds, explore factions, and prepare for epic adventures in a world of magic, mystery, and heroism.

## Features

- **Character Creation:**  
  Build custom characters by selecting name, gender, and class (Barbarian, Warrior, Knight, Priest, Wizard, Rogue, Ranger, Druid).

- **Character List:**  
  View all created characters in a sortable table.

- **Guild Management:**  
  Create and manage guilds, set notification preferences, and view all guilds in a dedicated list.

- **Factions Explorer:**  
  Discover lore-rich factions fetched from a local API server.

- **Players Showcase:**  
  Meet a cast of pre-made heroes with fun facts and stats.

- **Authentication:**  
  Sign in to access character and guild creation features. Session management is handled via cookies.

- **Responsive UI:**  
  Modern, themed interface with custom styles and Google Fonts.

- **Unit Tested:**  
  Comprehensive unit tests for all major components and services.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Angular CLI](https://angular.dev/tools/cli)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Raking45/rpg-character-builder.git
   cd rpg-character-builder/rpg-character-builder
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Run the development server:**
   ```sh
   ng serve
   ```
   Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Usage

**Sign In:**  
Use one of the demo accounts (e.g., `warrior@fantasy.com` / `Warrior123`) to sign in.

**Create Characters & Guilds:**  
Access creation features after signing in.

**Explore Factions:**  
Visit the Character Faction page to see available factions.

**Meet Players:**  
Browse the Players page for sample heroes.

## Scripts

- `ng serve` — Start the Angular dev server.
- `ng build` — Build the project for production.
- `ng test` — Run unit tests with Karma.
- `node character-factions.js` — Start the local API server for factions.

## Project Structure

- `src/app/` — Angular components, services, and routes.
- `public/assets/` — Character and background images.
- `character-factions.js` — Node.js API server for factions.

## Demo Accounts

| Email                   | Password      |
|-------------------------|--------------|
| warrior@fantasy.com     | Warrior123   |
| barbarian@fantasy.com   | Barbarian123 |
| wizard@fantasy.com      | Wizard123    |
| theif@fantasy.com       | Thief123     |
| ranger@fantasy.com      | Ranger123    |

## License

This project is licensed under the MIT License. See LICENSE for details.

## Acknowledgments

- Inspired by classic tabletop RPGs and fantasy games.
- Built with Angular and Karma.
