# Rhoids in Space

A browser-based arcade game inspired by the classic 1980s Asteroids, with a humorous medical twist. Pilot an ointment tube spaceship, destroy floating skin lesions, and earn high scores!

## Features

- **Single-file game** - Entire game in one HTML file, no build process needed
- **Mouse + Keyboard controls** - Move your mouse to aim, use arrow keys/WASD to thrust, space to shoot
- **Power-ups** - Rapid-fire (2x shots + 2x score multiplier) and speed boost
- **Progressive difficulty** - More enemies and faster UFOs as your score increases
- **UFO enemies** - Intelligent flying saucers that target and shoot at you
- **Sound effects** - Procedural Web Audio API synthesis (laser, explosion, power-up sounds)
- **Particle effects** - Jet flames, explosions, and visual feedback
- **Leaderboard** - localStorage-based top 10 scores that persist across sessions
- **Responsive design** - Works on desktop and scales to different screen sizes

## How to Play

1. Open `hemorrhoids.html` in any modern web browser
2. Click "START GAME"
3. **Controls:**
   - **Mouse**: Move to aim the ship's tip at your cursor
   - **Arrow Keys or WASD**: Rotate (keyboard-only) or thrust forward
   - **Space**: Fire projectiles
   - **P**: Pause/unpause
   - **Esc**: Return to menu

## Game Mechanics

- **Destroy lesions** - Large → Medium → Small, each worth more points
- **Collect power-ups** - Yellow lightning is rapid-fire, cyan shoe is speed boost
- **Survive UFOs** - They appear randomly and become more frequent as your score increases
- **Clear waves** - Destroy all lesions to advance to the next wave with more enemies

## Architecture

Built with:
- **HTML5 Canvas** - 2D vector graphics rendering
- **Vanilla JavaScript** - No dependencies, modular entity system
- **Web Audio API** - Procedural audio synthesis
- **localStorage** - Leaderboard persistence

## Code Structure

- **Game State** - Score, lives, wave, entities
- **Entity Classes** - Ship, Lesion, UFO, Projectile, PowerUp, Particle
- **Collision Detection** - AABB and circular collision checks
- **Input Handler** - Keyboard and mouse controls
- **Audio System** - Procedural sound synthesis
- **Game Loop** - Update and render at 60fps

## Learning from the Code

This game is a great example of:
- Game loop architecture
- Entity management system
- Collision detection algorithms
- Canvas 2D graphics and transformations
- Web Audio API procedural sound
- Input handling (keyboard + mouse)
- Game state management
- localStorage usage

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## License

Public domain - learn, modify, and share freely!

## Play It

Open `hemorrhoids.html` in your web browser or host it on any web server.

Have fun and rack up those high scores! 🎮
