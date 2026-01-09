````md
# CodeNCollab – Real-Time Collaborative Code Editor

## 1. Project Overview

**CodeNCollab** is a web-based real-time collaborative code editor that enables multiple users to work together in a shared workspace. Users can collaboratively edit source code, manage files and folders, execute programs, communicate via chat, and collaborate visually using a drawing board. All changes are synchronized instantly across connected users.

The project simulates a modern collaborative software development environment and is intended for academic, educational, and team-based development use cases.

---

## 2. Objectives

- Provide a real-time collaborative coding environment  
- Enable simultaneous multi-user editing  
- Support structured file and folder management  
- Allow live code execution with real-time output  
- Facilitate communication using chat and presence indicators  
- Integrate AI-assisted code generation  
- Ensure low-latency synchronization across users  

---

## 3. Key Features

### 3.1 Real-Time Code Collaboration
- Multiple users can edit the same file concurrently  
- Instant synchronization using WebSockets  
- Live cursor tracking and editor activity indicators  

### 3.2 Room-Based Collaboration
- Unique Room ID for each collaborative workspace  
- Only users with the same Room ID can join a session  

### 3.3 File and Folder Management
- Create, rename, delete, and organize files and folders  
- Supports multi-file project structures  

### 3.4 Integrated Code Execution
- Execute code directly inside the editor  
- Real-time output display  
- Multi-language execution support  

### 3.5 AI Code Assistant
- Generates code based on user prompts  
- Assists in inserting or modifying code  
- Improves development efficiency  

### 3.6 Built-in Chat
- Real-time text-based communication  
- Helps coordinate collaboration activities  

### 3.7 Presence and Activity Awareness
- Online/offline user status  
- Join and leave notifications  
- Active editor indicators  

### 3.8 Syntax Highlighting and Customization
- Automatic syntax highlighting  
- Customizable themes, fonts, and editor settings  

### 3.9 Collaborative Drawing Board
- Shared whiteboard for diagrams and sketches  
- Real-time synchronization of drawings  

### 3.10 Project Export
- Download the entire workspace as a ZIP file  
- Useful for backups and academic submissions  

---

## 4. System Architecture

The project follows a client–server architecture:

- **Frontend:** Handles UI, code editor, file explorer, and user interactions  
- **Backend:** Manages rooms, users, real-time synchronization, and execution requests  
- **Communication:** Real-time updates handled using WebSockets  

---

## 5. Technology Stack

### Frontend
- React  
- TypeScript  
- React Router  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  

### Real-Time Engine
- Socket.io  

### Tools and Services
- Docker  
- Vercel  
- Piston API (code execution)  
- Pollinations AI (AI code generation)  
- Tldraw (collaborative drawing)  

---

## 6. Installation and Setup

### 6.1 Prerequisites
- Node.js (v18 or later)  
- npm  
- Modern web browser  

### 6.2 Installation Steps

1. Fork the repository on GitHub  

2. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/CodeNCollab.git
````

3. Create environment files

   **Frontend (`client/.env`)**

   ```bash
   VITE_BACKEND_URL=http://localhost:3000
   ```

   **Backend (`server/.env`)**

   ```bash
   PORT=3000
   ```

4. Install dependencies:

   ```bash
   npm install
   ```

   *(Run inside both `client` and `server` directories)*

5. Start the development servers

   **Backend**

   ```bash
   cd server
   npm run dev
   ```

   **Frontend**

   ```bash
   cd client
   npm run dev
   ```

6. Open the application:

   ```
   http://localhost:5173
   ```

---

## 7. Live Demo

[https://code-sync-live.vercel.app/](https://code-sync-live.vercel.app/)

---

## 8. Use Cases

* Academic group projects
* Online coding workshops
* Team-based software development
* Collaborative learning platforms

---

## 9. Limitations

* Requires stable internet connectivity
* Depends on third-party services for execution and AI features
* AI output quality depends on prompt clarity

---

## 10. Future Enhancements

* Role-based access control
* User authentication
* Version history and rollback
* Voice communication
* Enhanced AI-assisted debugging

---

## 11. License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## 12. Developer Information

* **Project Name:** CodeNCollab
* **Developer:** Nagesh
* **Role:** Full Stack Developer
* **Purpose:** Academic Project Submission

---

## 13. Conclusion

CodeNCollab demonstrates the practical application of modern web technologies to enable real-time collaborative software development. The project integrates code editing, execution, communication, and AI assistance into a unified platform, making it suitable for academic evaluation and real-world collaboration.

```
```
