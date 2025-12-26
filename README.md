FACED App
Fair AI-Assisted Controlled Exam Delivery
📌 Project Overview
FACED App is a web-based exam integrity monitoring prototype designed to support fair, ethical, and low-bandwidth online examinations.
Unlike traditional proctoring systems that rely on constant surveillance and automated cheating accusations, FACED App follows a human-in-the-loop approach.
The system records objective exam-related events and presents them for instructor review, while final decisions remain with humans — not AI.
AI assists monitoring. Humans decide outcomes.

❓ Problem Statement
Most existing online exam monitoring solutions suffer from:
Excessive surveillance and privacy concerns
High false-positive cheating accusations
Heavy bandwidth consumption
Automated judgments without human context
Poor usability in low-network or rural environments
Students are often penalized due to system behavior rather than actual malpractice.
There is a strong need for a lightweight, ethical, and deployable exam monitoring system that works in real-world conditions.

💡 Solution Approach
FACED App uses an event-based monitoring model instead of behavioral or emotion-based judgment.
Core Design Principles
No automatic cheating decisions
Only factual system events are recorded
Human reviewers make final decisions
Privacy-first and low-bandwidth friendly
Logged Events (MVP)
Keystroke activity (for behavioral analysis experiments)
Snapshot captures (on specific triggers)
Timestamped logs for review
All recorded data is stored locally and intended for controlled instructor review only.

⭐ Key Features (MVP)
Web-based exam interface
Lightweight Express.js backend
Keystroke logging via REST API
Snapshot image capture and storage
Static frontend serving
Local file-based logging
Designed for low-bandwidth environments
No continuous video or audio recording
🚫 What the System Does NOT Do
❌ No emotion detection
❌ No eye tracking or gaze analysis
❌ No background or room monitoring
❌ No continuous webcam or microphone recording
❌ No automated cheating verdicts
This design avoids ethical risks, false accusations, and psychological stress.
🛠️ Technology Stack (Current MVP)
Frontend
HTML
CSS
JavaScript
Backend
Node.js
Express.js
Storage
File-based storage (logs and snapshots)
AI / Logic
Event logging only (AI-assisted analysis planned for future versions)
📱 Application Type
✅ Web Application
Runs locally in a browser and is designed to be lightweight and accessible even under low-bandwidth conditions.

▶️ How to Run the Project
Prerequisites
Node.js installed
Steps
Copy code
Bash
git clone https://github.com/saravanabalajisciet-crypto/FACED-APP.git
cd FACED-APP
npm install
node server.js
Open your browser and visit:
Copy code

http://localhost:3000
📂 Project Structure
Copy code

FACED-APP/
├── README.md
├── package.json
├── package-lock.json
├── server.js
├── public/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── models/
├── logs/
│   └── keystrokes.txt
└── snapshots/
🎥 Demo Video
📽️ Demo Video (Google Drive)
👉 https://drive.google.com/file/d/1cFYwj5yQpYwIVRPzGHf89_YBlznrowJV/view?usp=drivesdk

⚖️ Ethical Design Note
FACED App is intentionally designed not to detect or declare cheating automatically.
The system:
Collects objective activity data
Preserves transparency
Avoids invasive surveillance
Keeps humans in control of decisions
This approach reduces legal, ethical, and institutional risks while improving trust.

🚀 Future Scope
AI-assisted anomaly analysis (human-reviewed)
Instructor dashboards
Secure audit logs
Offline-first enhancements
Mobile and Android versions
Cloud deployment support

👤 Author
Saravana Balaji
Coimbatore Institute of Engineering and Technology
🧠 Final Note
FACED App prioritizes fairness, transparency, and real-world usability over aggressive AI enforcement.
It is built to work in practical conditions — not ideal ones.

