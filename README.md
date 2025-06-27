# WELLSMADE.CO Landing Game

A playable browser game inspired by the Chrome "No Internet" T-Rex game, featuring a golden Border Collie chasing a squirrel through an endless side-scrolling adventure.

## 🎮 Game Features

- **Player Character**: Golden Border Collie that runs and jumps
- **AI Companion**: Squirrel that automatically jumps over obstacles
- **Endless Gameplay**: Side-scrolling game with increasing difficulty
- **Responsive Design**: Works on desktop and mobile devices
- **Background Music**: Looping music with mute/unmute functionality
- **Modern UI**: Clean design with Inter font and smooth animations

## 🕹️ How to Play

- **Desktop**: Press `SPACEBAR` to make the dog jump over obstacles
- **Mobile**: Tap anywhere on the screen to jump
- **Objective**: Help the Border Collie avoid obstacles and chase the squirrel
- **Scoring**: Score increases based on distance traveled
- **Game Over**: Hit an obstacle to end the game and see your final score

## 🚀 Running Locally

1. Navigate to the project directory: `/Users/wellshome01/Dev/FrankGame/`
2. Open `index.html` in any modern web browser
3. Click "START GAME" to begin playing
4. No server or additional setup required!

## 🌐 Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `wellsmade-landing-game` (or `FrankGame`)
3. Make it public
4. Don't initialize with README (we have our own)

### Step 2: Upload Files
```bash
# Navigate to your project folder
cd /Users/wellshome01/Dev/FrankGame

# Initialize git repository
git init

# Add files
git add .

# Commit files
git commit -m "Initial commit: WELLSMADE.CO landing game"

# Add remote origin (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/wellsmade-landing-game.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select "Deploy from a branch"
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Live Game
Your game will be available at:
```
https://YOUR_USERNAME.github.io/wellsmade-landing-game
```

*Note: It may take a few minutes for GitHub Pages to deploy your site.*

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Structure and Canvas for game rendering
- **CSS3**: Styling, animations, and responsive design
- **Vanilla JavaScript**: Game logic, physics, and audio
- **Web Audio API**: Background music generation
- **Canvas API**: 2D graphics rendering

### File Structure
```
FrankGame/
├── index.html          # Complete game in single file
└── README.md          # This documentation
```

### Key Features Implementation
- **Responsive Canvas**: Automatically adjusts to screen size
- **Physics Engine**: Gravity, jumping, and collision detection
- **AI Behavior**: Squirrel automatically jumps over obstacles
- **Audio System**: Web Audio API for browser-compatible music
- **Touch Support**: Mobile-friendly touch controls
- **Game States**: Start screen, playing, and game over states

## 🎨 Customization

### Changing Colors
Modify the CSS variables or JavaScript color values:
- Player (Border Collie): `#FFD700` (gold)
- Squirrel: `#8B4513` (brown)
- Background: Sky blue to green gradient
- Obstacles: Brown tree stumps

### Adjusting Difficulty
In the JavaScript section, modify:
- `gameSpeed`: Initial game speed
- `jumpPower`: How high characters jump
- `gravity`: How fast they fall
- Obstacle generation frequency

### Adding Sound Effects
The game includes generated background music. To add sound effects:
1. Create audio files or use Web Audio API
2. Add them to the appropriate game events (jump, collision, etc.)

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements:
- Additional characters or obstacles
- Power-ups and special effects
- Enhanced graphics or animations
- New game modes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🏃‍♂️ About WELLSMADE.CO

*"Where ideas run wild."*

This landing page showcases interactive web development and game design capabilities. Perfect for demonstrating modern web technologies in a fun, engaging way.

---

**Ready to play?** Open `index.html` and let the chase begin! 🐕🐿️
