# Mia Kingtide's Ocean Memory Match 🐙

A beautiful ocean-themed memory matching game with 3D card animations, multiple difficulty levels, and engaging gameplay features.

## 🎮 Features

### Core Gameplay
- **Memory Matching**: Classic card-matching gameplay with ocean creature images
- **3D Card Animations**: Smooth flip animations with perspective effects
- **Multiple Difficulty Levels**:
  - Easy: 6 pairs (3x4 grid)
  - Medium: 12 pairs (4x6 grid) 
  - Hard: 20 pairs (5x8 grid)
- **Star Rating System**: Earn 1-3 stars based on move efficiency
- **Timer & Move Counter**: Track your performance

### Interactive Features
- **Pause/Resume**: Take breaks during gameplay
- **Card Preview**: Brief preview of all cards before game starts
- **Progress Bar**: Visual tracking of matched pairs
- **Sound Effects**: Web Audio API sounds for flips, matches, and wins
- **Particle Effects**: Celebratory animations on matches
- **Confetti Victory**: Animated celebration when you win

### User Experience
- **Leaderboard**: Top 10 scores for each difficulty level
- **Best Score Tracking**: Personal best times and moves
- **Player Profiles**: Customizable player names
- **Share Scores**: Share your achievements with others
- **Keyboard Navigation**: Full keyboard accessibility support
- **Responsive Design**: Works on desktop, tablet, and mobile

### Accessibility
- **Reduced Motion**: Toggle for users sensitive to animations
- **High Contrast**: Improved visibility option
- **Sound Toggle**: Mute/unmute sound effects
- **Keyboard Support**: Arrow keys and Enter/Space for gameplay
- **Screen Reader**: ARIA labels and semantic HTML

## 🚀 Quick Start

### Local Development
1. Clone or download the project
2. Open `index.html` in your web browser
3. No build process required - it's a standalone HTML file!

### File Structure
```
oceanmatch/
├── index.html          # Main game file (HTML, CSS, JavaScript)
├── img/               # Ocean creature images
│   ├── 1.webp - 20.webp
│   └── Octopus.svg    # Card back design
└── README.md          # This file
```

## 🎯 How to Play

1. **Choose Difficulty**: Select Easy, Medium, or Hard mode
2. **Preview Cards**: All cards are shown briefly at the start
3. **Match Pairs**: Click cards to flip them and find matching pairs
4. **Win Conditions**: Match all pairs to complete the game
5. **Beat Your Best**: Try to complete with fewer moves and better time

### Controls
- **Mouse**: Click cards to flip
- **Keyboard**: 
  - Arrow keys to navigate
  - Enter/Space to flip selected card
  - P to pause (when game is active)

### Star Rating
- **3 Stars**: Excellent performance (fewest moves)
- **2 Stars**: Good performance 
- **1 Star**: Completed the game

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Animations, 3D transforms, responsive design
- **Tailwind CSS**: Utility-first styling framework
- **Vanilla JavaScript**: Game logic and interactions
- **Web Audio API**: Dynamic sound generation
- **LocalStorage**: Game settings and score persistence

### Key Features Implementation
- **3D Card Flips**: CSS `transform-style: preserve-3d` with `rotateY`
- **Smart Image Loading**: Graceful fallback from JPG → WEBP → PNG → SVG
- **Responsive Grid**: Dynamic grid layout based on difficulty
- **State Management**: Centralized game state with localStorage persistence
- **Animation Performance**: Hardware-accelerated CSS transforms

### Browser Compatibility
- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile**: iOS Safari, Android Chrome
- **Features**: Requires ES6+ and CSS3 3D transforms support

## 🎨 Customization

### Adding New Images
1. Add images to the `img/` folder
2. Name them sequentially (1.jpg, 2.jpg, etc.)
3. Supported formats: JPG, WEBP, PNG
4. Update `CONFIG.totalImagePool` in the JavaScript

### Difficulty Settings
Modify the `CONFIG.difficulties` object in the JavaScript:
```javascript
difficulties: {
    easy: { pairs: 6, moveThresholds: [14, 20] },
    medium: { pairs: 12, moveThresholds: [26, 36] },
    hard: { pairs: 20, moveThresholds: [40, 55] }
}
```

### Styling
- **Colors**: Modify CSS custom properties for ocean theme
- **Fonts**: Change Google Fonts in the `<head>` section
- **Animations**: Adjust timing in CSS keyframes

## 📱 Mobile Optimization

- **Touch-Friendly**: Large tap targets for mobile devices
- **Responsive Layout**: Adapts to different screen sizes
- **Performance**: Optimized animations for mobile hardware
- **Orientation**: Works in portrait and landscape modes

## 🔧 Configuration Options

### Game Settings (in localStorage)
- `mia-memory-settings`: User preferences
- `mia-memory-best-{difficulty}`: Best scores per difficulty
- `mia-memory-leaderboard-{difficulty}`: Top 10 scores

### Audio Settings
- Volume and sound type can be modified in the `playSound()` function
- Uses Web Audio API for real-time sound generation

## 🤝 Contributing

This is a standalone web game. To contribute:
1. Fork the project
2. Make improvements
3. Test across different browsers and devices
4. Ensure accessibility standards are maintained

## 📄 License

This project is open source. Please check the license file for details.

## 🐛 Known Issues

- Some older browsers may not support 3D transforms
- Image loading may vary based on network speed
- Sound effects require user interaction to initialize (browser security)

## 🌟 Acknowledgments

- Ocean creature imagery for the game cards
- Tailwind CSS for rapid UI development
- Web Audio API for dynamic sound generation
- CSS3 3D transforms for smooth animations

---

**Enjoy playing Mia Kingtide's Ocean Memory Match!** 🌊🐠🦀
