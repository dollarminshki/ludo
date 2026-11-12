# 🎲 minshki Classic Ludo 3D

A modern 3D Ludo board game built with Three.js - all in a single HTML file!

![Ludo 3D Game](https://img.shields.io/badge/Game-Ludo%203D-E53935?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-3D%20Graphics-000000?style=for-the-badge&logo=three.js)
![Single File](https://img.shields.io/badge/Single-HTML%20File-1E88E5?style=for-the-badge)

## 🎮 Game Modes

- **🤖 vs Computer** - Play against AI with difficulty selection (Easy/Normal/Hard)
- **👥 2 Players** - Local multiplayer (each controls 2 colors)
- **👥👥 4 Players** - Full 4-player local game

## ✨ Features

### Core Gameplay
- 🎲 **Dice Options** - Choose single die or two dice modes
- 🎲 **3D Dice Animation** - Watch actual dice roll in 3D above the board!
- ⚔️ **Unique Capture Mechanic** - Both pieces removed on capture (capturing counts as finished!)
- ⭐ **Safe Squares** - Star positions where pieces can't be captured
- 🏠 **Home Stretch** - Colored paths leading to the center finish zone

### Bonus Rolls
- 🎯 Single die mode: Roll 6 = bonus turn
- 🎯 Two dice mode: Roll double 6s = bonus turn
- ⚔️ Capture an opponent = bonus turn!
- ⚠️ Three consecutive double 6s = lose your turn

### Quality of Life
- 💾 **Auto-Save** - Game saves automatically after every move
- 📷 **Screenshot** - Download a picture of your game board
- 📤 **Share** - Share the game link with friends
- 🔊 **Sound Effects** - Toggle audio on/off
- ➕➖ **Zoom Controls** - Adjust camera distance
- 🏠 **Home Button** - Return to main menu anytime
- ▲ **Collapsible Controls** - Clean UI with expandable settings menu

### Visual Features
- 🎨 **3D Board** - Beautiful Three.js rendered game board
- ✨ **Smooth Animations** - GSAP-powered piece movements
- 🔆 **Piece Highlighting** - Valid moves clearly indicated
- ↓ **Dice Arrows** - Bouncing indicators show selectable dice
- 🎉 **Victory Confetti** - Colorful celebration on win
- 🔄 **Loading Screen** - Polished loading animation

## 🕹️ How to Play

1. **Start** - Roll a 6 to move a piece out of your home base
2. **Move** - Click a die to select it, then click a highlighted piece
3. **Capture** - Land on opponent's piece to capture (you get a bonus turn!)
4. **Win** - Get all 4 of your pieces to the center

## 🛠️ Technical Details

- **Single HTML File** - No build step, no dependencies to install
- **Three.js via CDN** - 3D rendering
- **GSAP via CDN** - Smooth animations
- **LocalStorage** - Game state persistence

## 📂 Project Structure

```
Classic Ludo 3D/
├── index.html    # The complete game
└── README.md     # This file
```

## 🚀 Running the Game

Simply open `index.html` in any modern web browser!

```bash
# Or serve locally
npx serve .
```

## 🎯 Game Rules

### Movement
- Pieces move clockwise around the 52-square path
- After completing a lap, pieces enter their colored home column
- Exact roll required to enter the center finish zone

### Capture Rules
- Land on an opponent's piece to capture it
- **Both pieces are removed** - captured returns home, capturing counts as finished
- Pieces on star squares (⭐) are safe from capture
- Your starting square is always safe for your pieces

### Winning
- First player to get all 4 pieces home wins!
- In 2-player mode, you control 2 colors (8 pieces total needed)

---

Made with ❤️ and AI assistance for the Nairaland 3D Ludo Challenge
