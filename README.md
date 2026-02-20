# 💅 Gl'amour Nail & Spa Resort

![Version](https://img.shields.io/badge/version-1.0.0-pink)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**A fun and relaxing spa management game where you build your dream beauty empire!**

[Play Now](#installation) | [Features](#features) | [How to Play](#how-to-play)

---

## 📖 Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Mechanics](#game-mechanics)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎮 About

**Glamour Nail & Spa Resort** is a browser-based time management game where you run your own luxury spa. Serve customers, earn money, upgrade your facilities, and climb the leaderboard to become the ultimate spa tycoon!

### Game Highlights

- 🏨 Manage a luxury spa with 4 different service stations
- 💰 Earn money and purchase upgrades for passive income
- ⭐ Level up system with progressive difficulty
- 🏆 Competitive leaderboard with score tracking
- 🎨 Beautiful gradient UI with smooth animations
- 📱 Fully responsive - works on desktop, tablet, and mobile

---

## ✨ Features

### 🎯 Core Gameplay

- **4 Service Stations**
  - 💅 Manicure Station - $50 per service
  - 🦶 Pedicure Station - $60 per service
  - 💆‍♀️ Facial Station - $80 per service
  - 💇‍♀️ Hair Styling Station - $100 per service

- **Customer Management**
  - Dynamic patience system
  - Visual feedback (happy 😊 to angry 😠)
  - Speed bonuses for quick service

- **Progression System**
  - Level up every 10 satisfied customers
  - Unlock additional station slots
  - Increasing rewards

### 🛍️ Upgrade Shop

Purchase amenities to boost your spa:

| Upgrade | Effect | Max Level |
|---------|--------|-----------|
| 💺 Massage Chairs | +10% patience per level + $5/min passive income | 5 |
| 🍪 Snack Bar | +15% patience per level + $8/min passive income | 5 |
| 🧃 Drink Station | +12% patience per level + $6/min passive income | 5 |
| 🏧 ATM Machine | +$25 tip bonus per level + $15/min passive income | 3 |

### 🏆 Leaderboard System

- **Score Calculation**: Money earned + (Level × 1000) + (Satisfied customers × 100)
- **Time Filters**: All Time, Today, This Week
- **Personal Stats**: Track your rank and best score
- **Local Storage**: Saves automatically to browser

### 💾 Save System

- Save progress when pausing the game
- Save score when returning to main menu
- Persistent leaderboard data
- Remembers your player name

---

## 🚀 Installation

### Option 1: Download and Play (Recommended)

1. **Download the game files**
   ```bash
   # Clone the repository
   git clone https://github.com/Unkn5wn/Spa-Game.git
   
   # Or download as ZIP and extract
   ```

2. **Open in browser**
   ```bash
   # Navigate to the folder
   cd Spa-Game
   
   # Open index.html in your browser
   # Double-click index.html OR
   # Right-click → Open with → Your Browser
   ```

3. **Start playing!** 🎮

### Option 2: Run with Local Server (Optional)

For better performance and testing:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
```

### Requirements

- ✅ Modern web browser (Chrome, Firefox, Safari, Edge)
- ✅ JavaScript enabled
- ✅ Local storage enabled (for save data)
- ❌ No internet connection required (works offline!)
- ❌ No installation or dependencies needed

---

## 🎯 How to Play

### Getting Started

1. **Launch the game** - Open `index.html` in your browser
2. **Click "Start Game"** - Begin your spa journey
3. **Serve customers** - Follow the on-screen instructions

### Step-by-Step Guide

#### 1️⃣ Customer Arrives
- Customers appear in the **Waiting Area** on the right
- Each customer shows:
  - Name (e.g., "Sophia")
  - Desired service (💅 Manicure)
  - Patience meter (😊 100%)

#### 2️⃣ Select Customer
- **Click** on any customer in the waiting area
- A modal opens showing the customer's details

#### 3️⃣ Choose Station
- **Click** the correct service station
- Match the customer's service request
- ✅ Correct = Proceed to next step
- ❌ Wrong = Try again!

#### 4️⃣ Drag to Station
- **Drag** the customer icon to the correct station area
- Drop them on the highlighted station
- Service begins automatically

#### 5️⃣ Collect Payment
- Wait for the service to complete (progress bar fills)
- Payment is collected automatically
- Earn bonuses for fast service! 💰

### 🎮 Controls

| Action | Input |
|--------|-------|
| Select Customer | Click/Tap |
| Choose Station | Click/Tap |
| Drag Customer | Mouse Drag / Touch Drag |
| Pause Game | Click "⏸️ Pause" button |
| Open Shop | Click "🛍️ Upgrade Shop" button |
| View Leaderboard | Click "🏆 Leaderboard" button |
| Return to Menu | Click "🏠 Main Menu" button |

### 💡 Pro Tips

1. **Serve Fast** - Higher patience = bigger tips!
2. **Buy Upgrades Early** - Passive income adds up over time
3. **Prioritize Angry Customers** - Save customers with low patience first
4. **Manage Multiple Stations** - Don't let stations sit empty
5. **Level Up** - Every 10 customers = new station slot unlocked

---

## 🎲 Game Mechanics

### Patience System

- Starts at 100% (+ upgrade bonuses)
- Decreases by 0.05% every 100ms (adjustable difficulty)
- Customer leaves if patience reaches 0%
- Visual indicators change with patience level

### Scoring System

```
Total Score = Money Earned + (Level × 1000) + (Satisfied Customers × 100)

Example:
Money: $5,000
Level: 10
Customers: 50
Score = 5,000 + (10 × 1,000) + (50 × 100) = 20,000 points
```

### Service Times

| Service | Duration | Base Price |
|---------|----------|------------|
| 💅 Manicure | 5 seconds | $50 |
| 🦶 Pedicure | 6 seconds | $60 |
| 💆‍♀️ Facial | 7 seconds | $80 |
| 💇‍♀️ Hair Styling | 8 seconds | $100 |

### Bonuses

- **Speed Bonus**
  - 70%+ patience: +$20
  - 40-70% patience: +$10
  - Below 40%: No bonus
  
- **Tip Bonus** (from ATM upgrade)
  - +$25 per ATM level

### Level Progression

- Every 10 satisfied customers = Level Up
- Random station gains +1 slot (max 5 slots per station)
- Difficulty remains constant (customer spawn rate: 1 every 10 seconds)

---

## 📁 File Structure

```
Spa-Game/
│
├── index.html              # Main HTML file
├── styles.css              # All styling and animations
├── game.js                 # Core game logic
├── leaderboard.js          # Leaderboard and scoring system
├── README.md               # This file
│
└── assets/ (optional)
    ├── screenshots/        # Game screenshots
    └── icons/              # Favicon, app icons
```

### File Descriptions

| File | Size | Description |
|------|------|-------------|
| `index.html` | ~20KB | Game structure, modals, UI elements |
| `styles.css` | ~35KB | Complete styling, animations, responsive design |
| `game.js` | ~30KB | Game logic, customer management, station control |
| `leaderboard.js` | ~10KB | Score calculation, localStorage management |

---

## 🛠️ Technologies Used

### Frontend

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with:
  - Flexbox & CSS Grid
  - Gradients & animations
  - Custom properties
  - Media queries (responsive)
- **JavaScript (ES6+)** - Game logic with:
  - Arrow functions
  - Template literals
  - Local Storage API
  - DOM manipulation

### Features

- ✅ No external dependencies
- ✅ No frameworks required
- ✅ Vanilla JavaScript
- ✅ Browser-based storage
- ✅ Fully offline capable

### Browser Compatibility

| Browser | Minimum Version |
|---------|----------------|
| Chrome | 60+ |
| Firefox | 55+ |
| Safari | 11+ |
| Edge | 79+ |
| Opera | 47+ |

---

## 🎨 Customization

### Change Difficulty

Edit `game.js` line ~685 in the `spawnCustomer()` function:

```javascript
// Easy mode (slower patience decay - 5+ minutes)
patienceDecay: 0.03

// Normal mode (recommended - 3+ minutes)
patienceDecay: 0.05

// Hard mode (faster patience decay - 1.5+ minutes)
patienceDecay: 0.10

// Expert mode (very fast - 1 minute)
patienceDecay: 0.15
```

### Adjust Prices

Edit `game.js` services array (around line 39):

```javascript
const services = [
    { name: 'Manicure', icon: '💅', duration: 5000, price: 50 },
    // Change 'price' to adjust earnings
    // Change 'duration' to adjust service time (in milliseconds)
];
```

### Modify Colors

Edit `styles.css` gradient colors:

```css
/* Main menu background */
background: linear-gradient(135deg, #ff6ec7 0%, #ff8fd4 100%);

/* Change #ff6ec7 to your preferred color */
```

### Adjust Customer Spawn Rate

Edit `game.js` in the `startGame()` function (around line 640):

```javascript
setInterval(() => {
    if (game.isRunning && !game.isPaused) {
        spawnCustomer();
    }
}, 10000); // Change 10000 to adjust spawn rate (in milliseconds)
```

---

## 🐛 Troubleshooting

### Game Won't Load

1. Check browser console (F12) for errors
2. Ensure JavaScript is enabled
3. Try clearing browser cache (Ctrl+Shift+Delete)
4. Use incognito/private mode to test
5. Make sure all 4 files are in the same folder

### Leaderboard Not Saving

1. Check if browser allows localStorage
   - Chrome: Settings → Privacy → Site Settings → Cookies
   - Firefox: Options → Privacy & Security → Cookies
2. Disable browser extensions temporarily
3. Check browser privacy settings
4. Don't use private/incognito mode for persistent saves

### Performance Issues

1. Close other browser tabs
2. Update to latest browser version
3. Try different browser
4. Reduce window size on mobile devices
5. Check CPU usage - close unnecessary programs

### Customers Not Appearing

1. Click "Start Game" button first
2. Wait 10 seconds for first customer
3. Check if game is paused (Resume button visible)
4. Refresh page and try again

### Drag and Drop Not Working

1. Make sure you're clicking on customers in waiting area first
2. Complete both steps: Select station → Drag to station
3. Try using mouse instead of trackpad
4. On mobile: Use finger touch and drag

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Bugs

1. Check existing issues first
2. Create detailed bug report with:
   - Browser and version
   - Operating system
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots if applicable
   - Console errors (F12 → Console tab)

### Suggesting Features

- Open an issue with `[Feature Request]` tag
- Describe the feature and use case
- Explain why it would improve the game
- Include mockups or examples if possible

### Pull Requests

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request with detailed description

### Development Guidelines

- Follow existing code style and structure
- Comment complex logic clearly
- Test on multiple browsers before submitting
- Update README if adding new features
- Keep commits atomic and well-described

---



## 📧 Contact

**Developer:** Unkn5wn  
**GitHub:** [@Unkn5wn](https://github.com/Unkn5wn)  
**Project Link:** [https://github.com/Unkn5wn/Spa-Game](https://github.com/Unkn5wn/Spa-Game)

---

## 🙏 Acknowledgments

- Emoji icons from Unicode Standard
- Inspiration from time management games like Diner Dash and Sally's Spa
- Community feedback and testing
- Font families from system defaults

---

## 📊 Statistics

- **Lines of Code:** ~2,500
- **Files:** 4 (HTML, CSS, JS, Leaderboard)
- **Current Version:** 1.0.0
- **Last Updated:** December 2024
- **Game Size:** ~95KB total

---

## 🎯 Roadmap

### Version 1.1 (Planned)

- [ ] 🔊 Sound effects and background music toggle
- [ ] 🎨 Multiple spa themes/skins
- [ ] 📱 Progressive Web App (PWA) support
- [ ] 🏆 Achievement system (badges)
- [ ] 💾 Export/Import save data

### Version 1.2 (Future)

- [ ] 👥 Staff hiring system
- [ ] 🌐 Online multiplayer leaderboard (Firebase)
- [ ] 🎭 Special events and holiday themes
- [ ] 📈 Detailed statistics dashboard
- [ ] 🎁 Daily rewards system

### Version 2.0 (Long-term)

- [ ] Story mode with campaign levels
- [ ] More service types (massage, waxing, makeup)
- [ ] Customizable spa layout
- [ ] VIP customers with special requests
- [ ] Mini-games between levels

---

## ⭐ Show Your Support

If you enjoyed this game:

- ⭐ **Star this repository** on GitHub
- 🐛 **Report bugs** to help improve it
- 💡 **Share your ideas** for new features
- 🔗 **Share with friends** who love management games
- 📝 **Write a review** or testimonial

---

## 🎮 Gameplay Tips & Strategies

### Beginner Strategy

1. Start with **Massage Chairs** (best patience boost)
2. Focus on serving customers quickly
3. Don't worry about upgrades until Level 3
4. Practice the drag-and-drop mechanic
5. Watch the patience meter closely

### Intermediate Strategy

1. Balance between patience upgrades and passive income
2. Aim for speed bonuses on every customer
3. Unlock all station slots by Level 8
4. Prioritize customers with low patience
5. Keep at least 2 stations occupied at all times

### Advanced Strategy

1. Max out ATM early for tip bonuses
2. Time customer spawns to avoid overcrowding
3. Focus on high-value services (Hair Styling)
4. Use passive income to fund expensive upgrades
5. Aim for perfect 100% patience completions

---

## 🔗 Useful Links

- [Report a Bug](https://github.com/Unkn5wn/Spa-Game/issues)
- [Request Feature](https://github.com/Unkn5wn/Spa-Game/issues)
- [View Source Code](https://github.com/Unkn5wn/Spa-Game)

---

## 📈 Version History

### v1.0.0 (December 2024)
- ✨ Initial release
- 🎮 4 service stations
- 🛍️ 4 upgrade types
- 🏆 Local leaderboard system
- 💾 Save/load functionality
- 📱 Mobile responsive design

---

<div align="center">

**Made with 💖 and JavaScript**

*Happy Gaming! 🎮💅✨*

---

If you find this project helpful, please consider giving it a ⭐ star!

**[⬆ Back to Top](#-glamour-nail--spa-resort)**

</div>

---

**Version 1.0.0** | Last Updated: December 2024 | Built with ❤️ and JavaScript
