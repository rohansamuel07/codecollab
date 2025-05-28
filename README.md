# 🧑‍💻 CodeCollab – Online Collaborative Code Compiler

🚀 **Live Demo:** [https://codecollab-1-e80c.onrender.com](https://codecollab-1-e80c.onrender.com)

---

## 📌 Overview

CodeCollab is a cloud-based code compiler that supports 10+ programming languages with real-time multi-user collaboration using WebSockets. It features an advanced editor, secure session sharing, and AI-powered code generation.

🔧 Built using **Monaco Editor**, **Piston API**, **Socket.IO**, **Pollinations AI**, and **Tldraw**.

🎯 Optimized backend execution to reduce runtime by 30%, improving performance and user experience.

---

## 🔮 Features

* 💻 Real-time collaboration on code editing across multiple files
* 📁 Create, open, edit, save, delete, and organize files and folders
* 💾 Download the entire codebase as a zip file
* 🚀 Unique room generation with room ID for collaboration
* 🌍 Support for 10+ programming languages
* 🌈 Syntax highlighting with auto-language detection
* 🚀 Code Execution within the collaboration environment
* ⏱️ Instant sync of code changes
* 📣 Notifications when users join or leave
* 👥 Online/offline user presence indicators
* 💬 Real-time group chat
* 🎩 Real-time tooltip showing who's editing
* 💡 AI-powered suggestions based on language
* 🔠 Customizable font size and font family
* 🎨 Multiple themes (light/dark)
* 🖌️ Collaborative Drawing Board (Tldraw)
* 🤖 Copilot Assistant for code generation and insertion
* 🔴 Live Preview feature

---

## ⚙️ Installation

### Method 1: Manual Installation

1. **Fork this repository**
   Click the **Fork** button in the top-right corner of this page.

2. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/Code-Sync.git
   ```

3. **Create `.env` files**

   **Frontend (`client/.env`):**

   ```
   VITE_BACKEND_URL=<your_server_url>
   ```

   **Backend (`server/.env`):**

   ```
   PORT=3000
   ```

4. **Install dependencies**

   ```bash
   npm install     # Run in both client and server directories
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

6. **Access the app**

   ```
   http://localhost:5173/
   ```
