# Snake Game 🐍

A modern, responsive Snake game built with HTML5 Canvas, CSS3, and vanilla JavaScript. Features a beautiful UI, smooth gameplay, and mobile support.

![Snake Game](https://img.shields.io/badge/Game-Snake-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Features

- **Smooth Gameplay**: Responsive controls with WASD and arrow keys
- **Mobile Friendly**: Touch controls for mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **High Score**: Persistent high score tracking using localStorage
- **Pause/Resume**: Ability to pause and resume the game
- **Game Over Screen**: Clear feedback with restart functionality
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 🚀 How to Play

1. Click "Start Game" to begin
2. Use **WASD** keys or **Arrow Keys** to control the snake
3. On mobile devices, use the on-screen directional buttons
4. Eat the red food to grow and increase your score
5. Avoid hitting the walls or the snake's own body
6. Press **P** or **Space** to pause/resume the game

## 🛠️ Installation & Local Development

### Option 1: Simple File Opening
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start playing!

### Option 2: Local Server
```bash
# Clone the repository
git clone https://github.com/yourusername/snake-game.git
cd snake-game

# Start a local server (Python 3)
python -m http.server 8000

# Or with Node.js (if you have http-server installed)
npx http-server

# Open your browser and go to http://localhost:8000
```

## 🌐 Deployment

This game is ready to be deployed on any static hosting platform:

### GitHub Pages
1. Fork this repository
2. Go to repository Settings → Pages
3. Select source: "Deploy from a branch"
4. Choose "main" branch and "/" (root) folder
5. Your game will be available at `https://yourusername.github.io/snake-game`

### Netlify
1. Create account on [Netlify](https://netlify.com)
2. Drag and drop the project folder to Netlify dashboard
3. Your game will be live instantly with a generated URL

### Vercel
1. Create account on [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Deploy with zero configuration

### Other Platforms
The game works on any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Surge.sh
- AWS S3 Static Hosting

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile, Firefox Mobile)

## 🎯 Game Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Move Up | ↑ or W | ↑ Button |
| Move Down | ↓ or S | ↓ Button |
| Move Left | ← or A | ← Button |
| Move Right | → or D | → Button |
| Pause/Resume | P or Space | Pause Button |
| Restart | R or Click Restart | Click Restart |

## 🔧 Technical Details

- **Framework**: Vanilla JavaScript (ES6+)
- **Graphics**: HTML5 Canvas API
- **Storage**: localStorage for high scores
- **Responsive**: CSS Grid and Flexbox
- **Performance**: Optimized game loop with `setInterval`
- **Mobile**: Touch event handling for mobile controls

## 📁 Project Structure

```
snake-game/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # Game logic and JavaScript
├── package.json        # Project metadata
└── README.md          # Project documentation
```

## 🎨 Customization

You can easily customize the game by modifying these variables in `script.js`:

```javascript
// Game settings
this.gridSize = 20;        // Size of each grid cell
gameSpeed = 150;           // Game speed in milliseconds
```

And colors in `styles.css`:

```css
/* Snake color */
.snake { background: #4CAF50; }

/* Food color */
.food { background: #e74c3c; }

/* Background gradient */
body { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎉 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built with modern web technologies
- Designed for optimal user experience across all devices

---

**Enjoy playing Snake! 🐍🎮**