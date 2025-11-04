
💬 WhatsApp Add-On (Privacy-Focused Expo App)

A privacy-first WhatsApp-inspired communication app built using Expo (React Native) with local storage architecture.
The project includes both Client (mobile app) and Server (optional backend) components, structured for modular scalability and complete data ownership.

🧱 Project Structure
📦 whatsapp-add-on
 ┣ 📂 Client        # Expo React Native frontend
 ┣ 📂 server        # Node.js / Express backend (optional)
 ┣ 📜 .gitignore
 ┣ 📜 data.yaml     # Configuration / metadata file
 ┗ 📜 README.md

🚀 Features
📸 Status

Auto-trims videos for status uploads.

Archives previously uploaded statuses.

Enables status reposting.

👥 Community

Create communities from individual users or groups.

Broadcast messages to all community members.

Simplified community management UI.

📞 Calls

Logs and tracks call history.

Entirely stored locally for maximum privacy.

💬 Chat

Real-time chat simulation using local device storage.

No external server storage — 100% user-controlled data.

Smooth, responsive, and intuitive interface.

⚙️ Tech Stack
Layer	Technology
Client	Expo (React Native), React Hooks, AsyncStorage
Server	Node.js, Express.js (optional)
Storage	Local device storage only
UI	React Native Paper / Custom Components
🔐 Privacy Highlights

Zero cloud storage — all data remains local.

No ads, analytics, or background tracking.

Data minimization — only essential information is processed.

🧩 Installation & Setup
Client (Expo)
cd Client
npm install
npx expo start

Server (Optional)
cd server
npm install
npm start

🧠 Future Roadmap

🔒 App Lock (PIN/Biometric)

☁️ Optional encrypted backup

🎨 Customizable UI themes

🔔 Local push notifications
