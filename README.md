# Turbo Drift - 2D Highway Racing Game

Play the live game on GitHub Pages: **[https://sidzooni-ctrl.github.io/car-game/](https://sidzooni-ctrl.github.io/car-game/)**

## ✨ Features & Enhancements

- **Progressive Speed Scaling**: Starts smoothly and gently (~55 KM/H) so players can get comfortable, then progressively accelerates up to high-octane highway speeds (~190+ KM/H) as your distance and score grow!
- **Pure Web Audio Synthesizer**: Procedural sound effects and dynamic engine rumble using native Web Audio API (no external audio files, 100% offline-ready):
  - Adaptive engine rumble pitch that responds to your car's speed and nitro state.
  - Upbeat coin collection chimes.
  - Turbo boost roar, near-miss whoosh, collision impact crunch, and game-over melodies.
  - Sound mute / unmute toggle in HUD with persistent setting.
- **Dynamic Multi-Vehicle Traffic**:
  - **Sedans**: Standard highway drivers.
  - **Racers / Sports Cars**: Faster vehicles that challenge your reflexes.
  - **Semi-Trucks**: Long heavy cargo trailers requiring careful overtaking.
  - **Police Cruisers**: Emergency cruisers with animated flashing blue & red sirens.
  - **Fair Traffic AI**: Guaranteed navigable openings so you never face an unavoidable wall.
- **Power-Ups & Pickups**:
  - 🪙 **Gold Coins**: Collect coins for score boosts and currency.
  - ⚡ **Turbo Nitro**: Instant burst of top speed with neon fire exhaust particles!
  - 🛡️ **Energy Shield**: Absorbs a collision crash to protect your vehicle.
  - 🧲 **Coin Magnet**: Automatically pulls nearby coins directly to your car.
- **Vehicle Customization**:
  - Choose between 4 distinct car models and paint jobs: *Cyber Phantom, Crimson Fury, Aurum GT, Viper Green*.
- **Game Mechanics & Immersion**:
  - **3 Lives (Hull Integrity)** with temporary invulnerability flicker on hit.
  - **Near-Miss Rewards**: Overtake cars closely to earn bonus points and "CLOSE CALL!" awards.
  - **Dynamic Headlight Cones**: Headlight beams illuminate the dark asphalt ahead.
  - **Roadside Scenery**: Lush trees, streetlights, curbs, and animated rumble strips.
  - **Particle Effects**: Exhaust smoke, nitro flame bursts, coin sparkles, and collision fragments.
  - **High Score & Stats**: High score and coin banking saved in browser `localStorage`.
  - **Pause Menu**: Press `P` or `Esc` or tap the pause button anytime.

## 🎮 Controls

### Desktop Keyboard:
- **Steer Left**: `←` Left Arrow or `A`
- **Steer Right**: `→` Right Arrow or `D`
- **Turbo Boost**: `↑` Up Arrow, `W`, or `Space`
- **Brake**: `↓` Down Arrow or `S`
- **Pause / Resume**: `P` or `Esc`

### Mobile / Touchscreen:
- **On-Screen Buttons**: Steering arrows (◀ ▶), Brake, and Nitro Boost (🚀) buttons.
- **Canvas Swipe / Tap**: Swipe or tap left/right to navigate lanes smoothly.