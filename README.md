/tetris-clock
│
├── index.html        # The main display
├── style.css         # Neon aesthetics and "Line Clear" animations
├── /src
│   ├── main.js       # The "Heartbeat" (ticks every second)
│   ├── engine.js     # Tetris physics and "Hard Drop" logic
│   ├── solver.js     # The "Sabotage & Rebuild" algorithm (the brains)
│   └── maps.js       # 5x3 coordinate arrays for digits 0-9
└── /assets           # Classic 8-bit sound effects (SFX)
