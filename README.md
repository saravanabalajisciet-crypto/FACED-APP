FACED App
Fair AI-Assisted Controlled Exam Delivery
📌 Project Overview
FACED App is a web-based remote exam integrity system designed to support fair and reliable online examinations, especially in low-bandwidth and unstable network conditions.
Unlike traditional online proctoring tools that rely on aggressive surveillance and automated cheating accusations, FACED App follows a human-in-the-loop approach.
The system records verifiable exam integrity events and presents them transparently to teachers, while final decisions are always made by humans, not AI.
AI assists. Humans decide.

❓ Problem Statement
Most existing online exam monitoring solutions suffer from:
High false positives
Over-surveillance and privacy violations
Heavy bandwidth usage
Automated judgments without context
Poor performance in rural or low-network regions
Students are often penalized for technical issues rather than actual malpractice, leading to distrust and stress.
There is a need for an ethical, lightweight, and deployable exam integrity system that works in real-world conditions.

💡 Solution Approach
FACED App adopts an event-based integrity model instead of behavioral judgment.
Core principles:
No automatic cheating accusations
Only factual system events are logged
Teachers retain full authority
Privacy-first and low-bandwidth friendly
The system records objective, timestamped events such as:
Identity verification status
App focus loss / tab switching
Exam pause and resume
Network interruptions
Exam start and submission
These events are shown as a clear timeline to instructors for transparent review.

⭐ Key Features
Web-based exam interface (HTML, CSS, JavaScript)
Identity verification using face recognition (entry & re-entry only)
Tab switching / focus loss detection
Automatic exam pause and lock on focus loss
Offline-tolerant exam flow
Event logging for exam integrity
Teacher-controlled resume or termination
Minimal data collection and privacy-first design
🚫 What the System Does NOT Do
❌ No emotion detection
❌ No eye-tracking or gaze analysis
❌ No room or background monitoring
❌ No continuous video/audio recording
❌ No automated cheating verdicts
This avoids ethical risks, false accusations, and psychological stress.

🛠️ Technology Stack (MVP – Current Implementation)
Frontend
HTML
CSS
JavaScript
Backend
Python
Flask (REST APIs for exam flow, event logging, and instructor actions)
Database
SQLite (used for MVP and local persistence)
AI / Logic Used
Face recognition for identity verification only
Rule-based logic for exam state and tab-switch detection
(AI assists monitoring; it does not make decisions)

Deployment (MVP)
Local / test  server
📱 Application Type
✅ Web Application
(Designed to be lightweight and accessible even under low-bandwidth conditions. Mobile and Android app versions are planned as future enhancements.)
http://localhost:3000

Demo Video
📽️ Demo Video Link:
👉 https://drive.google.com/file/d/1cFYwj5yQpYwlVRPzGHf89_YBIznrowJV/view?usp=drivesdk

⚖️ Ethical Design Note
FACED App is intentionally designed not to detect or declare cheating automatically.
The system:
Preserves exam integrity evidence
Prevents uncontrolled exam continuation
Ensures transparency
Respects student privacy
This approach reduces legal, ethical, and institutional risks while improving trust.
🚀 Future Scope
Android mobile application
Teacher dashboards with analytics
Multi-exam and institution support
Secure audit exports
Cloud-scale deployment
Compliance tooling for universities

👤 Author
Saravana Balaji
Coimbatore Institute of Engineering and Technology

🧠 Final Note
FACED App prioritizes reliability, fairness, and human judgment over aggressive AI enforcement.
It is designed to work in real-world conditions—not ideal ones.


