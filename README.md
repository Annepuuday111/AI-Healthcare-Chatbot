<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,35:FFA94D,70:4DABF7,100:845EF7&height=200&section=header&text=AI%20Healthcare%20ChatBot&fontSize=44&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Gemini-powered%20health%20assistant%20for%20patients%2C%20doctors%20%26%20admins&descSize=16&descAlignY=58" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=845EF7&center=true&vCenter=true&width=700&lines=Ask+health+questions+in+plain+language;Upload+medical+reports+for+AI+analysis;Book+appointments+with+specialists;Runs+on+web%2C+Android+%26+iOS" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/Express%205-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
<img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white" alt="Capacitor"/>

<br/>

<img src="https://img.shields.io/badge/Status-Active-20C997?style=for-the-badge" alt="Status"/>
<img src="https://img.shields.io/github/stars/Annepuuday111/AI-Healthcare-Chatbot?style=for-the-badge&color=845EF7" alt="Stars"/>
<img src="https://img.shields.io/github/last-commit/Annepuuday111/AI-Healthcare-Chatbot?style=for-the-badge&color=4DABF7" alt="Last Commit"/>
<img src="https://img.shields.io/github/repo-size/Annepuuday111/AI-Healthcare-Chatbot?style=for-the-badge&color=FF6B6B" alt="Repo Size"/>

<br/><br/>

<a href="https://ai-healthcare-chat-bot.vercel.app"><img src="https://img.shields.io/badge/🚀%20Live%20Demo-Open%20App-FF6B6B?style=for-the-badge" alt="Live Demo" height="40"/></a>

<br/><br/>

[About](#-about) • [Features](#-features) • [Tech Stack](#️-tech-stack) • [Architecture](#️-architecture) • [Getting Started](#-getting-started) • [Mobile Apps](#-mobile-apps-capacitor) • [Author](#-author)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📖 About

**AI Healthcare ChatBot** is a full-stack healthcare assistant. Patients chat with an AI assistant (Google Gemini) about symptoms, medications and their own records, upload medical reports for analysis, and book appointments with doctors by specialization. Doctors manage their appointment queue and issue prescriptions, and admins manage doctors, patients and specializations. The React frontend is also packaged as native **Android** and **iOS** apps with Capacitor.

> ⚠️ **Disclaimer:** This project is for informational and educational purposes only. Always consult a qualified medical professional for health concerns.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## ✨ Features

### 🧑 Patient
- 💬 **AI chat assistant** – Gemini answers health questions with context from the user's appointments and prescriptions (tries several Gemini models in order as fallbacks)
- 🩺 **Symptom analysis, health queries & appointment-scheduling** chat modes; serious issues are flagged with an appointment suggestion
- 📄 **Medical report analysis** – upload an image or PDF and get an AI summary via `/api/analyze-report`
- 🎙️ **Voice input** using the browser Web Speech API
- 📅 **Appointments** – book a doctor by specialization, date and time; track pending / confirmed / completed status
- 💊 **Medications** – view prescriptions with dosage, timing and status
- 📋 **Patient records** timeline and 🔔 **notifications**
- 📊 **Insights dashboard** with Recharts line, bar and pie charts

### 👨‍⚕️ Doctor
- Appointment queue with confirm / complete actions
- Write prescriptions that notify the patient
- Change password

### 🛡️ Admin
- Add, edit and delete doctors
- View registered patients
- Manage medical specializations

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=react,ts,vite,nodejs,express,mongodb,vercel&theme=light" alt="Tech icons"/>

</div>

| Layer | Technology |
| :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) |
| **UI & Charts** | ![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge) ![Lucide](https://img.shields.io/badge/Lucide-F56565?style=for-the-badge&logo=lucide&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express%205-000000?style=for-the-badge&logo=express&logoColor=white) |
| **Database** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white) |
| **AI** | ![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white) (`@google/generative-ai`) |
| **Mobile** | ![Capacitor](https://img.shields.io/badge/Capacitor%208-119EFF?style=for-the-badge&logo=capacitor&logoColor=white) ![Android](https://img.shields.io/badge/Android-34A853?style=for-the-badge&logo=android&logoColor=white) ![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white) |
| **Hosting** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) (frontend) · ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black) (backend) |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🏗️ Architecture

```text
React + Vite SPA (web / Capacitor Android & iOS)
        │   axios / fetch  →  VITE_API_URL
        ▼
Express 5 API (backend/server.js)
        ├── Mongoose  →  MongoDB  (User, Appointment, Prescription, Notification, Specialization)
        └── @google/generative-ai  →  Gemini  (/api/chat, /api/analyze-report)
```

### 📂 Project Structure

```text
AI-Healthcare-Chatbot/
├── backend/
│   ├── server.js            # Express API, Mongoose models, Gemini routes
│   └── package.json
├── src/
│   ├── App.tsx              # Main app: login, chat, patient / doctor / admin views
│   ├── App.css
│   ├── admin.css
│   ├── appLogic.ts
│   ├── config.ts            # API_URL (VITE_API_URL or http://localhost:5001/api)
│   ├── components/          # Chat, Dashboard, Sidebar
│   ├── types.ts
│   └── main.tsx
├── public/
├── android/                 # Capacitor Android project
├── ios/                     # Capacitor iOS project
├── capacitor.config.ts      # appId com.aihealth.app, webDir dist
├── run-android.sh           # Build → cap sync → run on Android
├── vercel.json              # SPA rewrites
├── vite.config.ts
└── package.json
```

### 🔌 API Endpoints

| Method | Endpoint | Purpose |
| :--- | :--- | :--- |
| `POST` | `/api/register`, `/api/login` | Patient / doctor / admin auth |
| `GET` | `/api/doctors`, `/api/specializations` | Doctor and specialization lists |
| `POST` `PATCH` `GET` | `/api/appointments`, `/api/appointments/:id`, `/api/appointments/:email` | Book, update status, list appointments |
| `GET` `POST` | `/api/prescriptions/:email`, `/api/prescriptions` | Prescriptions |
| `GET` `POST` | `/api/notifications/:email`, `/api/notifications` | Notifications |
| `POST` | `/api/chat` | Gemini chat |
| `POST` | `/api/analyze-report` | Gemini medical-report analysis |
| `GET` `POST` `PUT` `DELETE` | `/api/admin/doctors`, `/api/admin/patients`, `/api/admin/specializations` | Admin management |
| `POST` | `/api/doctors/change-password` | Doctor password change |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🚀 Getting Started

### Prerequisites

- Node.js 20+ and npm
- MongoDB (local or MongoDB Atlas)
- A Google Gemini API key

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Annepuuday111/AI-Healthcare-Chatbot.git
   cd AI-Healthcare-Chatbot
   ```

2. **Configure and start the backend**
   ```bash
   cd backend
   npm install
   ```
   Create `backend/.env`:
   ```env
   MONGODB_URI=mongodb://localhost:27017/aihealthchatbot
   GEMINI_API_KEY=your_gemini_api_key
   PORT=5001
   ```
   ```bash
   npm start          # runs node server.js on http://localhost:5001
   ```

3. **Start the frontend** (in a new terminal, from the project root)
   ```bash
   npm install
   npm run dev
   ```
   By default the app calls `http://localhost:5001/api`. To point it elsewhere, create `.env.local` in the root:
   ```env
   VITE_API_URL=https://your-backend-url/api
   ```

4. **Build for production**
   ```bash
   npm run build      # tsc -b && vite build → dist/
   npm run preview
   ```

### ☁️ Deployment

| Part | Platform | Settings |
| :--- | :--- | :--- |
| Frontend | Vercel | Build `npm run build`, output `dist`, env `VITE_API_URL` |
| Backend | Render | Root `backend`, build `npm install`, start `node server.js`, env `MONGODB_URI`, `GEMINI_API_KEY` |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📱 Mobile Apps (Capacitor)

```bash
# Android – builds the web app, syncs Capacitor and launches on a device/emulator
./run-android.sh

# Or step by step
npm run build
npx cap sync android
npx cap open android   # opens Android Studio

# iOS (macOS + Xcode)
npm run build
npx cap sync ios
npx cap open ios
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🗺️ Roadmap

- [x] Gemini chat with record-aware context
- [x] Medical report upload & analysis
- [x] Patient, doctor and admin portals
- [x] Android & iOS builds with Capacitor
- [ ] Password hashing and token-based auth
- [ ] Appointment reminders via push notifications

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a Pull Request

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 👨‍💻 Author

<div align="center">

### Annepu Uday Kumar

<a href="https://github.com/Annepuuday111"><img src="https://img.shields.io/badge/GitHub-Annepuuday111-845EF7?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://annepuudaykumar.netlify.app"><img src="https://img.shields.io/badge/Portfolio-Visit-FF6B6B?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio"/></a>

</div>

<br/>

<div align="center">⭐ If you like this project, give it a star!</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:845EF7,35:4DABF7,70:FFA94D,100:FF6B6B&height=120&section=footer" width="100%"/>
