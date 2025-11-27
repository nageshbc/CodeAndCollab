# Code Sync

Code Sync is a powerful real-time collaborative code editor designed to make teamwork effortless. Multiple users can join a shared workspace using a unique room ID and work together on files, folders, executed code, drawings, and chats—all synchronized instantly.

## ✨ Key Features

- **Real-Time Code Collaboration** – Edit multiple files simultaneously with instant updates.
- **Project Management** – Create, rename, delete, and organize files & folders.
- **Full Project Export** – Download the complete workspace as a ZIP archive.
- **Room-Based Collaboration** – Generate and share unique room IDs.
- **Automatic Syntax Highlighting** – Language-aware formatting for clean and readable code.
- **Integrated Code Execution** – Run code inside the environment with live output.
- **Instant Sync** – Every change reflects across all connected users without delay.
- **User Activity Awareness** – See who joins, leaves, or edits a file.
- **Presence Indicators** – Online/offline status for all participants.
- **Built-in Chat** – Communicate instantly with collaborators.
- **Live Cursor & Editing Tooltip** – Track who is editing what.
- **Smart Suggestions** – Auto-completion tailored to language context.
- **Customizable Editor** – Choose fonts, themes, and sizes.
- **Collaborative Drawing Board** – Sketch ideas visually in real time.
- **AI Code Assistant** – Generate, modify, or insert code using integrated AI.

## 🚀 Live Demo

Try it here: **https://code-sync-live.vercel.app/**

## 🛠️ Technology Stack

- **Frontend:** React, TypeScript, React Router, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Real-Time Engine:** Socket.io
- **Tools & Deployment:** Docker, Vercel

---

## ⚙️ Installation Guide

### **Option 1: Manual Installation**

1. **Fork the repository** on GitHub.
2. **Clone your copy:**
   ```bash
   git clone https://github.com/<your-username>/Code-Sync.git
   ```
3. **Create environment files** in both the frontend and backend.

   **Frontend .env**
   ```bash
   VITE_BACKEND_URL=<your_backend_url>
   ```

   **Backend .env**
   ```bash
   PORT=3000
   ```

4. **Install dependencies:**
   ```bash
   npm install    # Run this inside both /client and /server
   ```

5. **Start the development servers:**

   **Client:**
   ```bash
   cd client
   npm run dev
   ```

   **Server:**
   ```bash
   cd server
   npm run dev
   ```

6. **Visit the app:**
   http://localhost:5173/

### **Option 2: Docker Deployment**

1. Install **Docker Desktop**.
2. Pull the prebuilt images:
   ```bash
   docker pull sahilatahar/code-sync-server:latest
   docker pull sahilatahar/code-sync-client:latest
   ```
3. Run the containers:
   ```bash
   docker run -d -p 3000:3000 --name code-sync-server sahilatahar/code-sync-server:latest
   docker run -d -p 5173:5173 --name code-sync-client sahilatahar/code-sync-client:latest
   ```
4. Open the app in your browser:
   http://localhost:5173/

---

## 📌 Planned Enhancements

- Role-based permissions and administrator controls.

## 🤝 How to Contribute

Contributions are welcome! Please refer to `CONTRIBUTING.md` for guidelines.

## 📜 License

Distributed under the **MIT License**. See the `LICENSE` file for details.

## 🙌 Credits & Resources

Special thanks to the tools and libraries that power this project:
- **Piston API** – For code execution support
- **Tldraw** – For collaborative drawing capabilities
- **Pollinations AI** – For AI-driven features

---

## 👨‍💻 Developer
**Developed and maintained by Nagesh.**
