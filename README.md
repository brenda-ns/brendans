# Creative Portfolio & Mini-Game

A personal portfolio website with an interactive Pac-Man style mini-game embedded in the background.  
Move your mouse to control the character, avoid ghosts, collect points, and survive as long as possible.

## Features

- **Fully responsive** portfolio layout with sections: Home, About, Skills, Projects, Contact.
- **Interactive canvas background** – the game runs behind the content, following your mouse everywhere.
- **Unique ghost abilities**:
  - 🔴 **Red** – aggressively chases the player.
  - 🟠 **Orange** – roams randomly and spawns points around itself.
  - 🩷 **Pink** – shoots webs that **stun** the player for 1.5 seconds.
  - 🔵 **Blue** – leaves a long trail (snake) that damages on touch.
- **Points system** – collect all dots to get a bonus and refresh the map.
- **Lives system** – start with 3 lives. Touching ghosts or the blue trail reduces lives.
- **Stun effect** – web immobilizes the player temporarily.
- **Floating HUD** – shows score and lives in the top right corner.

## Technologies Used

- HTML5 / CSS3
- JavaScript (Canvas API)
- Google Fonts (Poppins)
- Font Awesome icons

## How to Play

- Move your **mouse** anywhere on the screen → the yellow character follows.
- **Avoid** the red, pink and blue ghosts (direct touch kills you).
- **Do not touch** the blue snake trail.
- **Collect** all yellow dots to score points.
- If you step on a **pink web**, you get stunned for a moment.
- The **orange ghost** creates new points around itself.

## Installation

1. Clone the repository or download the files.
2. Place all files in the same folder: `index.html`, `style.css`, `engine.js`.
3. Open `index.html` in any modern browser.

No external images or dependencies required – everything is drawn with Canvas.

## Credits

- Developed by **Brenda NS**  
- Portfolio concept and game integration inspired by the creative work of **Bruno Moraes** ([GitHub](https://github.com/brunomoraesdigital)).  
- AGPL-3.0 license – see footer for details.

## License

AGPL-3.0 – You may use, modify and distribute this code, but any derivative work must also be open source under the same license.
