Open index.html in your browser

Double-click the file, OR
Right-click → Open with → Browser
Play! 🎮

Method 2: Local Server (Optional)
bash
# Python
python -m http.server 8000

# Node.js
npx http-server

# Then visit: http://localhost:8000
✅ Requirements
Modern web browser (Chrome 60+, Firefox 55+, Safari 11+)
JavaScript enabled
No internet needed after download!
📖 How to Play
Basic Workflow
Code
Customer Arrives → Click Customer → Select Station → Drag to Station → Collect Payment
Step-by-Step Guide
<details> <summary><b>1️⃣ Customer Arrives</b> (Click to expand)</summary> <br>
Customers appear in the Waiting Area with:

👤 Name (e.g., "Sophia")
💅 Service needed
😊 Patience meter (100%)
Watch the patience meter! Customers leave if it reaches 0%.

</details> <details> <summary><b>2️⃣ Select Customer</b></summary> <br>
Click any customer in the waiting area
A modal shows their service request
Choose quickly if multiple customers are waiting!
</details> <details> <summary><b>3️⃣ Choose Station</b></summary> <br>
Click the matching station
✅ Correct: Opens drag screen
❌ Wrong: Try again
Tip: Match the emoji icons!

</details> <details> <summary><b>4️⃣ Drag to Station</b></summary> <br>
Drag customer to the highlighted station
Drop in the correct area
Service starts automatically!
Mobile: Use touch and drag

</details> <details> <summary><b>5️⃣ Collect Payment</b></summary> <br>
Progress bar shows service completion
Payment collected automatically
Earn bonuses for fast service! 💰
</details>
🎮 Controls
Action	Desktop	Mobile
Select Customer	Click	Tap
Choose Station	Click	Tap
Drag Customer	Click & Drag	Touch & Drag
Pause Game	Click "⏸️ Pause"	Tap Button
Open Shop	Click "🛍️ Shop"	Tap Button
💡 Strategy & Tips
🥉 Beginner Tips
Start with Massage Chairs - Best patience boost
Watch the patience meter - Serve angry customers first
Learn the stations - Match icons quickly
Don't rush - Accuracy over speed at first
🥈 Intermediate Strategy
Speed is key - Aim for 70%+ patience for bonuses
Keep stations busy - Always have 2+ working
Balance upgrades - Mix patience + passive income
Level up fast - More slots = more customers
🥇 Advanced Tactics
Max ATM early - $75 tip bonus at level 3
Perfect timing - Start services when new customers spawn
Focus high-value - Prioritize Hair Styling ($100)
Manage queue - Keep 3-4 customers waiting max
🎲 Game Mechanics
💯 Scoring System
JavaScript
Total Score = Money Earned + (Level × 1,000) + (Customers × 100)

Example High Score:
$15,000 + (Level 15 × 1,000) + (80 customers × 100) = 38,000 points
🎁 Bonus System
Condition	Bonus
70%+ Patience	+$20 Speed Bonus
40-69% Patience	+$10 Speed Bonus
ATM Level 1	+$25 Tip Bonus
ATM Level 2	+$50 Tip Bonus
ATM Level 3	+$75 Tip Bonus
📊 Upgrade Costs
Upgrade	Level 1	Level 2	Level 3	Level 4	Level 5	Max Effect
💺 Chairs	$200	$300	$450	$675	$1,013	+50% patience, $25/min
🍪 Snacks	$300	$480	$768	$1,229	$1,966	+75% patience, $40/min
🧃 Drinks	$250	$375	$563	$844	$1,266	+60% patience, $30/min
🏧 ATM	$500	$1,000	$2,000	-	-	+$75 tips, $45/min
📁 Project Structure
Code
Spa-Game/
│
├── index.html          # Main game file (HTML structure)
├── styles.css          # All styling and animations
├── game.js             # Game logic and mechanics
├── leaderboard.js      # Scoring and leaderboard system
└── README.md           # This file
File Details
File	Lines	Description
index.html	~400	Game UI, modals, service stations
styles.css	~1,200	Responsive design, animations, themes
game.js	~900	Customer AI, station management, progression
leaderboard.js	~300	Local storage, scoring, rankings
🎨 Customization
Change Difficulty
File: game.js (line ~685)

JavaScript
patienceDecay: 0.05,  // Current: Normal (3 min wait)

// Easy Mode (5+ minutes)
patienceDecay: 0.03,

// Hard Mode (1.5 minutes)
patienceDecay: 0.10,
Adjust Prices
File: game.js (line ~39)

JavaScript
const services = [
    { name: 'Manicure', icon: '💅', duration: 5000, price: 50 },
    //                                            Change ^^^^
];
Change Theme Colors
File: styles.css (line ~50)

CSS
/* Main pink theme */
background: linear-gradient(135deg, #ff6ec7 0%, #ff8fd4 100%);

/* Try blue theme */
background: linear-gradient(135deg, #4ec7ff 0%, #6ec7ff 100%);

/* Try purple theme */
background: linear-gradient(135deg, #9b59b6 0%, #8e44ad 100%);
🐛 Troubleshooting
<details> <summary><b>🚫 Game won't load</b></summary> <br>
Solutions:

Check browser console (F12) for errors
Enable JavaScript in browser settings
Clear cache: Ctrl+Shift+Delete
Try incognito/private mode
Use a different browser
</details> <details> <summary><b>💾 Leaderboard not saving</b></summary> <br>
Solutions:

Allow cookies/local storage
Don't use private browsing mode
Check browser privacy settings
Disable strict tracking protection
</details> <details> <summary><b>🎮 Drag & drop not working</b></summary> <br>
Solutions:

Click customer first, then select station
Try using mouse instead of trackpad
On mobile: Use finger, not stylus
Refresh page and try again
</details> <details> <summary><b>👥 No customers appearing</b></summary> <br>
Solutions:

Click "Start Game" button first
Wait 10 seconds for first customer
Check if game is paused (Resume button)
Refresh page
</details>
🤝 Contributing
We welcome contributions! Here's how:

🐛 Report Bugs
Check existing issues
Create new issue with:
Browser & version
Steps to reproduce
Expected vs actual behavior
Screenshots
💡 Suggest Features
Open feature request
Describe feature and use case
Explain benefits
🔧 Submit Code
Fork the repository
Create branch: git checkout -b feature/YourFeature
Commit: git commit -m 'Add YourFeature'
Push: git push origin feature/YourFeature
Open Pull Request
📜 License
MIT License - Free to use, modify, and distribute!

Code
Copyright (c) 2024 Spa Game

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
Full License Text

🎯 Roadmap
🚀 Version 1.1 (Coming Soon)
 🔊 Sound effects & background music
 🎨 Multiple color themes
 🏆 Achievement badges
 💾 Export/import save data
 📱 PWA support (install as app)
🌟 Version 2.0 (Future)
 👥 Hire staff members
 🌐 Online leaderboard
 🎭 Seasonal events
 📊 Statistics dashboard
 🎁 Daily rewards
View Full Roadmap

📊 Stats
<div align="center">
Metric	Value
Total Code	~2,800 lines
Game Size	~95 KB
Languages	HTML, CSS, JavaScript
Dependencies	0
Version	1.0.0
</div>
🙏 Acknowledgments
🎨 Emoji icons from Unicode Standard
💡 Inspired by Diner Dash & Sally's Spa
🎮 Built with vanilla JavaScript
💖 Made with love and coffee
📞 Contact & Links
<div align="center">
Developer: @Unkn5wn

🐛 Report Bug • 💡 Request Feature • ⭐ Star Project

</div>
<div align="center">
⭐ Star this repo if you enjoyed the game!
Made with 💖 and JavaScript

Last Updated: December 2024

⬆ Back to Top

</div> ```
✨ Key Improvements:
Better Visual Hierarchy

Clear sections with emojis
Centered headers
Consistent spacing
Collapsible Sections

How to Play is expandable
Troubleshooting is collapsible
Easier to navigate
Tables & Visual Data

Cleaner comparison tables
Upgrade costs visible
Better statistics display
Color-Coded Badges

Professional look
Eye-catching
GitHub-style formatting
Quick Links

Jump to sections easily
Report bugs directly
Better navigation
This version is much more scannable and easier to read! 🎯✨
