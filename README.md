# REFLEX — Precision Reaction Timer

A visually immersive reaction time testing application built with vanilla JavaScript and Three.js. Test your reflexes with real-time 3D visual feedback, statistical tracking, and a sleek cyberpunk-inspired interface.


## ? Features

- **Reaction Time Testing**: Measure your response time with millisecond precision
- **Immersive 3D Visuals**: Dynamic 3D shapes that transform based on game state
- **False Start Detection**: Penalizes early clicks to ensure accurate measurements
- **Session Statistics**: Track attempts, average time, and personal best
- **History Log**: View your recent reaction times with best attempts highlighted
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Keyboard Support**: Use spacebar for rapid testing
- **Ambient Visuals**: Floating particles, pulsing rings, and dynamic lighting

## ?? How It Works

1. **Start** the game — the target zone turns amber
2. **Wait** for the signal (random delay 1-5 seconds)
3. **Click immediately** when the zone turns green and the 3D shape explodes
4. **View your reaction time** in milliseconds
5. **Track your progress** with real-time statistics
6. **Avoid false starts** — clicking early records an error

## ??? Technologies Used

- **HTML5/CSS3**: Semantic markup with CSS custom properties for theming
- **Vanilla JavaScript**: Pure JS implementation with no frameworks
- **Three.js**: Dynamic 3D graphics and particle systems
- **Google Fonts**: Syne (display) and JetBrains Mono (monospace)
- **CSS Grid/Flexbox**: Responsive layout system
- **CSS Animations**: Smooth transitions and visual feedback

## ?? Visual States

The interface provides clear visual feedback for each game state:

| State | Color | 3D Effect | Description |
|-------|-------|-----------|-------------|
| Idle | Gray | Static | Ready to start |
| Waiting | Amber | Gentle rotation | Random delay before signal |
| Ready | Green | Rapid spinning + explosion | Click now! |
| Result | Blue | Slow rotation | Display reaction time |
| Error | Red | Shake animation + particles | False start detected |

## ?? Statistics Tracking

- **Attempts**: Total number of tests performed
- **Average**: Mean reaction time (excluding false starts)
- **Best**: Fastest reaction time in current session
- **History Log**: Chronological list of all attempts with best times highlighted

## ?? Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/reflex-reaction-timer.git