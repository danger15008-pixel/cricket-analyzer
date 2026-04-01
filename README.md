🏏 Cricket AI Analyzer
An AI-powered web app that analyzes cricket images (batting, bowling, fielding) and provides professional coaching feedback.
🚀 Features
📸 Upload cricket images
🧠 AI-powered analysis using vision models
🏏 Detects:
Player type (batsman/bowler)
Technique & posture
Mistakes
Improvement tips
⭐ Gives performance rating out of 10
🌐 Full-stack (React + Node.js)
🛠️ Tech Stack
Frontend: React (Vite)
Backend: Node.js + Express
AI: OpenAI Vision API
Upload Handling: Multer
📂 Project Structure

cricket-analyzer/
│
├── frontend/        # React app
│   ├── App.jsx
│   ├── main.jsx
│   └── index.html
│
├── backend/         # Node.js server
│   ├── server.js
│   └── package.json
│
└── README.md
⚙️ Setup Instructions
1️⃣ Clone the repository
Bash
git clone https://github.com/your-username/cricket-analyzer.git
cd cricket-analyzer
2️⃣ Backend Setup
Bash
cd backend
npm install
👉 Add your API key in server.js:
JavaScript
apiKey: "YOUR_OPENAI_API_KEY"
Run server:
Bash
node server.js
3️⃣ Frontend Setup
Bash
cd frontend
npm install
npm run dev
🌐 Usage
Open browser at:

http://localhost:5173
Upload a cricket image
Click Analyze
Get:
Technique feedback
Mistakes
Improvement tips
🏏 Example Use Cases
Fast bowling action analysis
Batting stance improvement
Shot technique feedback
Fielding posture correction
📱 APK Conversion
You can convert this website into an Android app using:
Capacitor
OR tools like web-to-app converters
🔒 Environment Variables
For production, store your API key securely:

OPENAI_API_KEY=your_key_here
⚡ Future Improvements
🎥 Video analysis (frame-by-frame)
🧍 Pose detection
📊 Player performance tracking
🔐 User login system
🌍 Live deployment
🤝 Contributing
Feel free to fork and improve the project.
📜 License
This project is open-source and free to use.
💡 Author
Built by you 🚀 (with AI assistance)
