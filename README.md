💅 Glamour Nail & Spa Resort
A fun and relaxing spa management game where you build your dream beauty empire!

Game Description
Welcome to Glamour Nail & Spa Resort - the ultimate spa management experience! Take charge of your own luxury spa and serve happy customers while building your beauty empire from the ground up.

🎮 Gameplay
Run a bustling spa with 4 service stations: Manicure 💅, Pedicure 🦶, Facial 💆‍♀️, and Hair Styling 💇‍♀️. Click on waiting customers, match them to the right service, and drag them to their station. Keep customers happy by serving them quickly before their patience runs out!

✨ Features
🏪 4 Service Stations - Manage multiple beauty services simultaneously
⭐ Level Up System - Earn XP and unlock more station slots as you progress
💰 Upgrade Shop - Purchase massage chairs, snack bars, drink stations, and ATMs to boost customer satisfaction and earn passive income
🏆 Leaderboard - Compete with other players and save your high scores
📊 Score System - Based on money earned, level reached, and satisfied customers
⏸️ Save Progress - Pause and save your game anytime
🎯 Goal
Serve customers efficiently, earn money, level up, and become the ultimate spa tycoon! The better you serve (faster service = happier customers), the more tips you earn!

Perfect for: Casual gamers, time management fans, and anyone who loves spa and beauty themes! 💖

Play now and build your glamorous spa empire! ✨🎮💅

A fun and relaxing spa management game where you build your dream beauty empire!

Play Now | Features | How to Play | Screenshots

📖 Table of Contents
About
Features
Installation
How to Play
Game Mechanics
File Structure
Technologies Used
Contributing
License
Contact
🎮 About
Glamour Nail & Spa Resort is a browser-based time management game where you run your own luxury spa. Serve customers, earn money, upgrade your facilities, and climb the leaderboard to become the ultimate spa tycoon!

Game Highlights
🏨 Manage a luxury spa with 4 different service stations
💰 Earn money and purchase upgrades for passive income
⭐ Level up system with progressive difficulty
🏆 Competitive leaderboard with score tracking
🎨 Beautiful gradient UI with smooth animations
📱 Fully responsive - works on desktop, tablet, and mobile
✨ Features
🎯 Core Gameplay
4 Service Stations

💅 Manicure Station - $50 per service
🦶 Pedicure Station - $60 per service
💆‍♀️ Facial Station - $80 per service
💇‍♀️ Hair Styling Station - $100 per service
Customer Management

Dynamic patience system
Visual feedback (happy 😊 to angry 😠)
Speed bonuses for quick service
Progression System

Level up every 10 satisfied customers
Unlock additional station slots
Increasing difficulty
🛍️ Upgrade Shop
Purchase amenities to boost your spa:

Upgrade	Effect	Max Level
💺 Massage Chairs	+10% patience per level + $5/min passive income	5
🍪 Snack Bar	+15% patience per level + $8/min passive income	5
🧃 Drink Station	+12% patience per level + $6/min passive income	5
🏧 ATM Machine	+$25 tip bonus per level + $15/min passive income	3
🏆 Leaderboard System
Score Calculation: Money earned + (Level × 1000) + (Satisfied customers × 100)
Time Filters: All Time, Today, This Week
Personal Stats: Track your rank and best score
Local Storage: Saves automatically to browser
💾 Save System
Save progress when pausing the game
Save score when returning to main menu
Persistent leaderboard data
Remembers your player name
🚀 Installation
Option 1: Download and Play (Recommended)
Download the game files

bash
# Clone the repository
git clone https://github.com/yourusername/glamour-spa-resort.git

# Or download as ZIP and extract
Open in browser

bash
# Navigate to the folder
cd glamour-spa-resort

# Open index.html in your browser
# Double-click index.html OR
# Right-click → Open with → Your Browser
Start playing! 🎮

Option 2: Run with Local Server (Optional)
For better performance and testing:

bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
Requirements
✅ Modern web browser (Chrome, Firefox, Safari, Edge)
✅ JavaScript enabled
✅ Local storage enabled (for save data)
❌ No internet connection required (works offline!)
❌ No installation or dependencies needed
🎯 How to Play
Getting Started
Launch the game - Open index.html in your browser
Click "Start Game" - Begin your spa journey
Serve customers - Follow the on-screen tutorial
Step-by-Step Guide
1️⃣ Customer Arrives
Customers appear in the Waiting Area on the right
Each customer shows:
Name (e.g., "Sophia")
Desired service (💅 Manicure)
Patience meter (😊 100%)
2️⃣ Select Customer
Click on any customer in the waiting area
A modal opens showing the customer's details
3️⃣ Choose Station
Click the correct service station
Match the customer's service request
✅ Correct = Proceed to next step
❌ Wrong = Try again!
4️⃣ Drag to Station
Drag the customer icon to the correct station area
Drop them on the highlighted station
Service begins automatically
5️⃣ Collect Payment
Wait for the service to complete (progress bar fills)
Payment is collected automatically
Earn bonuses for fast service! 💰
🎮 Controls
Action	Input
Select Customer	Click/Tap
Choose Station	Click/Tap
Drag Customer	Mouse Drag / Touch Drag
Pause Game	Click "⏸️ Pause" button
Open Shop	Click "🛍️ Upgrade Shop" button
View Leaderboard	Click "🏆 Leaderboard" button
Return to Menu	Click "🏠 Main Menu" button
💡 Pro Tips
Serve Fast - Higher patience = bigger tips!
Buy Upgrades Early - Passive income adds up over time
Prioritize Angry Customers - Save customers with low patience first
Manage Multiple Stations - Don't let stations sit empty
Level Up - Every 10 customers = new station slot unlocked
🎲 Game Mechanics
Patience System
Starts at 100% (+ upgrade bonuses)
Decreases by 0.05% every 100ms
Customer leaves if patience reaches 0%
Visual indicators change with patience level
Scoring System
Code
Total Score = Money Earned + (Level × 1000) + (Satisfied Customers × 100)

Example:
Money: $5,000
Level: 10
Customers: 50
Score = 5,000 + (10 × 1,000) + (50 × 100) = 20,000 points
Service Times
Service	Duration	Base Price
💅 Manicure	5 seconds	$50
🦶 Pedicure	6 seconds	$60
💆‍♀️ Facial	7 seconds	$80
💇‍♀️ Hair Styling	8 seconds	$100
Bonuses
Speed Bonus
70%+ patience: +$20
40-70% patience: +$10
Below 40%: No bonus
Tip Bonus (from ATM upgrade)
+$25 per ATM level
Level Progression
Every 10 satisfied customers = Level Up
Random station gains +1 slot (max 5 slots per station)
Difficulty remains constant (customer spawn rate)
📁 File Structure
Code
glamour-spa-resort/
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
File Descriptions
File	Size	Description
index.html	~20KB	Game structure, modals, UI elements
styles.css	~35KB	Complete styling, animations, responsive design
game.js	~30KB	Game logic, customer management, station control
leaderboard.js	~10KB	Score calculation, localStorage management
🛠️ Technologies Used
Frontend
HTML5 - Semantic markup
CSS3 - Modern styling with:
Flexbox & CSS Grid
Gradients & animations
Custom properties
Media queries (responsive)
JavaScript (ES6+) - Game logic with:
Classes & modules
Arrow functions
Template literals
Local Storage API
Features
✅ No external dependencies
✅ No frameworks required
✅ Vanilla JavaScript
✅ Browser-based storage
✅ Fully offline capable
Browser Compatibility
Browser	Minimum Version
Chrome	60+
Firefox	55+
Safari	11+
Edge	79+
Opera	47+
🎨 Customization
Change Difficulty
Edit game.js line ~685:

JavaScript
// Easy mode (slower patience decay)
patienceDecay: 0.03

// Normal mode (recommended)
patienceDecay: 0.05

// Hard mode (faster patience decay)
patienceDecay: 0.10
Adjust Prices
Edit game.js services array:

JavaScript
const services = [
    { name: 'Manicure', icon: '💅', duration: 5000, price: 50 },
    // Change 'price' to adjust earnings
];
Modify Colors
Edit styles.css gradient colors:

CSS
/* Main theme color */
background: linear-gradient(135deg, #ff6ec7 0%, #ff8fd4 100%);

/* Change #ff6ec7 to your preferred color */
🐛 Troubleshooting
Game Won't Load
Check browser console (F12) for errors
Ensure JavaScript is enabled
Try clearing browser cache (Ctrl+Shift+Delete)
Use incognito/private mode
Leaderboard Not Saving
Check if browser allows localStorage
Disable browser extensions temporarily
Check browser privacy settings
Performance Issues
Close other browser tabs
Update to latest browser version
Try different browser
Reduce window size on mobile devices
🤝 Contributing
Contributions are welcome! Here's how you can help:

Reporting Bugs
Check existing issues first
Create detailed bug report with:
Browser and version
Steps to reproduce
Expected vs actual behavior
Screenshots if applicable
Suggesting Features
Open an issue with [Feature Request] tag
Describe the feature and use case
Explain why it would improve the game
Pull Requests
Fork the repository
Create feature branch (git checkout -b feature/AmazingFeature)
Commit changes (git commit -m 'Add AmazingFeature')
Push to branch (git push origin feature/AmazingFeature)
Open Pull Request
Development Guidelines
Follow existing code style
Comment complex logic
Test on multiple browsers
Update README if needed
📝 License
This project is licensed under the MIT License - see below for details:

Code
MIT License

Copyright (c) 2024 Glamour Spa Resort

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
📧 Contact
Developer: Your Name
Email: your.email@example.com
GitHub: @yourusername
Project Link: https://github.com/yourusername/glamour-spa-resort

🙏 Acknowledgments
Emoji icons from Unicode Standard
Inspiration from time management games like Diner Dash
Community feedback and testing
📊 Statistics
Lines of Code: ~2,500
Development Time: [Your timeframe]
Current Version: 1.0.0
Last Updated: December 2024
🎯 Roadmap
Planned Features
 🔊 Sound effects and background music
 🎨 Multiple spa themes/skins
 👥 Staff hiring system
 🏆 Achievement system
 📱 Progressive Web App (PWA) support
 🌐 Online multiplayer leaderboard
 💾 Cloud save support
 🎭 Special events and challenges
 📈 Detailed statistics dashboard
 🎁 Daily rewards system
Future Improvements
Enhanced animations
More service types
Customizable spa layout
Story mode
Tutorial improvements
⭐ Show Your Support
If you enjoyed this game:

⭐ Star this repository
🐛 Report bugs to help improve it
💡 Share your ideas for new features
🔗 Share with friends who love management games!
<div align="center">
Made with 💖 by [Your Name]

Happy Gaming! 🎮💅✨

</div>
🎮 Quick Links
Play Online Demo (Coming Soon)
Report a Bug
Request Feature
View Source Code
Version 1.0.0 | Last Updated: December 2024 | Built with ❤️ and JavaScript
