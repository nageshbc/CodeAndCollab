# Code Sync

![logo](https://github.com/sahilatahar/Code-Sync/assets/100127570/d1ff7f52-a692-4d51-b281-358aeab9156e)

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

![GitHub contributors](https://img.shields.io/github/contributors/sahilatahar/Code-Sync?style=for-the-badge&color=48bf21)
![GitHub Repo stars](https://img.shields.io/github/stars/sahilatahar/Code-Sync?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/sahilatahar/Code-Sync?style=for-the-badge&color=d7af2d)
![GitHub pull requests](https://img.shields.io/github/issues-pr/sahilatahar/Code-Sync?style=for-the-badge&color=f47373)
![GitHub License](https://img.shields.io/github/license/sahilatahar/Code-Sync?style=for-the-badge&color=e67234)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fsahilatahar%2FCode-Sync&label=Repo%20Views&countColor=%2337d67a&labelStyle=upper)

## 🔮 Features

- 💻 Real-time collaboration on code editing across multiple files
- 📁 Create, open, edit, save, delete, and organize files and folders
- 💾 Option to download the entire codebase as a zip file
- 🚀 Unique room generation with room ID for collaboration
- 🌍 Comprehensive language support for versatile programming
- 🌈 Syntax highlighting with auto-language detection
- 🚀 Code Execution inside collaboration environment
- ⏱️ Instant updates and synchronization
- 📣 Notifications for user join/leave events
- 👥 Online/offline user presence list
- 💬 Real-time group chatting
- 🎩 Real-time tooltip for users currently editing
- 💡 Auto suggestion based on programming language
- 🔠 Adjustable font size & font family
- 🎨 Multiple themes
- 🎨 Collaborative Drawing (real-time)
- 🤖 Copilot: AI-powered code assistant

## 🚀 Live Preview

https://code-sync-live.vercel.app/

## 💻 Tech Stack

React • TypeScript • React Router • Tailwind CSS • Node.js • Express.js • Socket.io • Git • Docker • Vercel

## ⚙️ Installation

### Method 1: Manual Installation

1. **Fork this repository**
2. **Clone:**
   ```bash
   git clone https://github.com/<your-username>/Code-Sync.git
   ```
3. **Create `.env` files**

   **Frontend**
   ```bash
   VITE_BACKEND_URL=<your_server_url>
   ```

   **Backend**
   ```bash
   PORT=3000
   ```

4. **Install dependencies**
   ```bash
   npm install   # Run in both client and server
   ```

5. **Start the servers**

   **Frontend:**
   ```bash
   cd client
   npm run dev
   ```

   **Backend:**
   ```bash
   cd server
   npm run dev
   ```

6. **Open:**
   http://localhost:5173/

### 🎥 Setup Help
   https://youtu.be/zVHwOmU0aqo

---

### Method 2: Docker Installation

1. Install Docker Desktop
2. Pull images:
   ```bash
   docker pull sahilatahar/code-sync-server:latest
   docker pull sahilatahar/code-sync-client:latest
   ```
3. Run containers:
   ```bash
   docker run -d -p 3000:3000 --name code-sync-server sahilatahar/code-sync-server:latest
   docker run -d -p 5173:5173 --name code-sync-client sahilatahar/code-sync-client:latest
   ```
4. Visit:
   http://localhost:5173/

---

## 🔮 Next Release Features

- Admin Permission System

## 🤝 Contribute

Read the contribution guidelines in `CONTRIBUTING.md`.

## 🌟 Support

If this project helps you, consider starring ⭐ the repo!

## 🧾 License

MIT License — see `LICENSE`.

## 🌟 Appreciation for Resources

Special thanks to:

- **Piston API (EMKC)**
- **Tldraw**
- **Pollinations AI**
