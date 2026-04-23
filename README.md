🏏 IPL 2026 Prediction Tracker

A fun, real-time web app to track IPL match predictions among friends — complete with leaderboard, stats, and live sync.

🚀 Live Demo

👉 https://ipl---predictor.web.app

🎯 Features
🧠 Pre-match Predictions
Predict match winners before the game starts
🏆 Dynamic Leaderboard
Automatically updates scores based on correct predictions
⚡ Real-time Sync (Firebase)
All data is synced across devices instantly
👥 Multi-user Support (No Login Required)
Simple name-based participation (Adi, Sipi, Nithin, Tijil)
🔥 Streaks & Badges
Leader 👑
Comeback 🐸
Climber 🚀
Hot streak 🔥
📊 Stats & Insights
Accuracy tracking
Prediction history
Performance comparison
🎨 Modern UI/UX
Smooth animations
Dark theme
Responsive design
🧩 Tech Stack
Frontend: HTML, CSS, JavaScript
Backend / Database: Firebase Firestore
Hosting: Firebase Hosting
⚙️ How It Works
Users select a match and predict the winner
Predictions are stored in Firestore
Admin updates match results
Points are calculated:
✅ Correct prediction → +1 point
❌ Wrong prediction → 0
Leaderboard updates automatically
🧠 Ranking Logic
Players are ranked based on total points
In case of a tie:
The player who got the latest correct prediction ranks higher
📁 Project Structure
index.html     → Main application (UI + logic)
firebase.json  → Hosting configuration
.firestore     → Firebase project config
🔧 Setup (For Developers)
1. Clone the repo
git clone https://github.com/your-username/ipl_prediction_tracker.git
cd ipl_prediction_tracker
2. Add Firebase Config

Inside index.html, replace:

const firebaseConfig = {
  apiKey: "YOUR_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
};
3. Enable Firestore

In Firebase Console → Firestore → Rules:

allow read, write: if true;
4. Deploy
firebase deploy
⚠️ Note
This project is built for personal/friend usage
Firestore rules are open (allow read, write: true)
For production apps, proper authentication should be added
💡 Future Improvements
🔐 Authentication (Google Sign-In)
⏳ Lock predictions after toss
📱 PWA support (install as app)
📈 Advanced analytics dashboard
🌍 Public leaderboard mode
👨‍💻 Author

Aditya Kolluru

🏁 Final Thoughts

Started as a fun idea among friends — turned into a fully deployed real-time web app 🚀
