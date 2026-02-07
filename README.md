# Mia Kingtide 🐙

The official home for the **Mia Kingtide** book series and ocean-themed games. Features links to all 6 books on Amazon, 4 browser-based games, and a downloadable Windows solitaire game.

## 📚 The Book Series

The home page showcases all 6 Mia Kingtide books with cover images and direct Amazon links:

### Chapter Books
1. **The Octopus' Gift** — [Amazon](https://www.amazon.com/Mia-Kingtide-Friendship-Self-Confidence-Adventures/dp/B0F9DFKTZ6/)
2. **Guardian of the Coast** — [Amazon](https://www.amazon.com/Mia-Kingtide-Protecting-Kingtides-Adventures/dp/B0DVT5PBQP/)
3. **Journey to the Sea of Cortez** — [Amazon](https://www.amazon.com/Mia-Kingtide-exploring-Kingtides-Adventures/dp/B0F1LY4HPT/)
4. **The Vanishing Sanctuary** — [Amazon](https://www.amazon.com/Mia-Kingtide-Vanishing-innovation-Adventures/dp/B0FY22H14T/)

### Illustrated Children's Books
1. **The Octopus' Gift: Where It All Began** — [Amazon](https://www.amazon.com/Mia-Kingtide-Self-Confidence-Illustrated-Adventures/dp/B0GGHZTFRG/)
2. **The Octopus' Gift: The Secret of The Shell** — [Amazon](https://www.amazon.com/Mia-Kingtide-Discovery-Illustrated-Adventures/dp/B0GK8HPLX2/)

[View all books on Amazon](https://www.amazon.com/stores/Luke-Kilpatrick/author/B0DNBNF2ZK)

## 🎮 Online Games

### Ocean Memory Match (`oceanmatch.html`)
Classic card-matching game with 3D flip animations.
- **3 Difficulty Levels**: Easy (6 pairs), Medium (12 pairs), Hard (20 pairs)
- **Star Rating**: 1-3 stars based on move efficiency
- **Timer & Move Counter**: Track your performance
- **Pause/Resume**: Take breaks during gameplay
- **Card Preview**: Brief preview before game starts
- **Particle Effects & Confetti**: Celebratory animations
- **Keyboard Navigation**: Full keyboard accessibility

### Ocean Speed Match (`speedmatch.html`)
Fast-paced reaction game — are the two creatures the same?
- **20 Rounds**: Race against the clock each round
- **Streak Bonuses**: Build combos for higher scores
- **Accuracy Tracking**: See how well you performed
- **Best Score Persistence**: Beat your high score

### Sanctuary Sort (`sanctuarysort.html`)
Sort ocean creatures into their correct categories.
- **Two Modes**: "Where is it?" (5 habitat bins) and "Story vs Real" (2 bins)
- **Time Attack**: 60-second countdown with continuous play
- **Practice Mode**: Sort all 20 tiles at your own pace
- **Streak Bonuses**: Every 5 correct answers earns bonus points
- **Confetti Celebration**: Animated confetti on new high scores
- **Drag & Drop**: Desktop drag-and-drop or mobile tap-to-sort
- **How to Play Tutorial**: Instructions shown before game starts

### Ocean Focus (`oceanfocus.html`)
Tap the target creature as fast as you can!
- **Two Modes**: "Find Creature" and "Find Habitat"
- **60-Second Time Attack**: Race against the clock
- **3-2-1 Countdown**: Build anticipation before each game
- **Progressive Difficulty**: Grid grows from 12 to 16 to 20 pictures
- **Level Up Notifications**: Visual feedback when grid expands
- **Streak Celebrations**: Every 5-streak triggers a bonus animation
- **Timer Penalty Display**: See "-1s" when you tap wrong
- **Correct Tile Hints**: Wrong taps briefly highlight the correct answer
- **How to Play Tutorial**: Instructions shown before game starts

## 🃏 Kingtide Solitaire: Baker's Dozen

A standalone Windows solitaire game with ocean-themed artwork featuring Mia Kingtide characters. Free download available from the landing page (`kingtidesol/index.html`).
- **Baker's Dozen Solitaire**: Classic card game variant
- **Ocean Artwork**: Cards featuring characters from the book series
- **Windows App**: Standalone desktop application (~14.5 MB)

## 🔧 Shared Features (All Online Games)

- **Sound Effects Toggle**: Mute/unmute audio feedback
- **Haptic Feedback Toggle**: Enable/disable vibration on mobile
- **Reduced Motion Toggle**: Disable animations for accessibility
- **Leaderboard**: Top 10 scores per game mode/difficulty
- **Player Name Input**: Customizable names for leaderboard
- **Confetti on Win**: Celebratory animation on high scores
- **Consistent Navigation**: Emoji-labeled nav links across all games
- **Responsive Design**: Works on desktop, tablet, and mobile

## 🚀 Quick Start

1. Clone or download the project
2. Open `index.html` in your web browser
3. No build process required — all games are standalone HTML files!

### File Structure
```
oceanmatch/
├── index.html          # Home page (books + games)
├── index.htm           # Home page (alternate extension)
├── oceanmatch.html     # Memory Match game
├── speedmatch.html     # Speed Match game
├── sanctuarysort.html  # Sanctuary Sort game
├── oceanfocus.html     # Ocean Focus game
├── kingtidesol/        # Kingtide Solitaire
│   ├── index.html      # Download landing page
│   └── KingtideSolitaire-Windows.zip
├── manifest.json       # PWA manifest
├── .htaccess           # Apache configuration
├── img/                # Game & book images
│   ├── 1.webp - 20.webp  # Ocean creature tiles
│   ├── book1-4.jpg        # Chapter book covers
│   ├── childrens1-2.jpg   # Children's book covers
│   └── Octopus.svg        # Card back design & favicon
├── LICENSE             # Apache 2.0 License
└── README.md           # This file
```

## 🛠️ Technical Details

- **HTML5 / CSS3 / Vanilla JavaScript** — No build tools required
- **Tailwind CSS** — Utility-first styling via CDN
- **Web Audio API** — Dynamic sound generation
- **LocalStorage** — Settings, scores, and leaderboard persistence
- **CSS 3D Transforms** — Card flip animations (Memory Match)
- **PWA Support** — Manifest and service worker ready

### Browser Compatibility
- Chrome, Firefox, Safari, Edge (latest versions)
- iOS Safari, Android Chrome
- Requires ES6+ and CSS3 3D transforms

## 📄 License

Copyright 2025 Luke Kilpatrick. Licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

---

 [Explore the Mia Kingtide books on Amazon](https://www.amazon.com/stores/Luke-Kilpatrick/author/B0DNBNF2ZK) | 🌐 [PitterPatterDiving.com](https://pitterpatterdiving.com)
