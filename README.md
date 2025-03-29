# 🚀 DEBUG - AI Code Reviewer

![License](https://img.shields.io/badge/license-MIT-green) ![Vite](https://img.shields.io/badge/Vite-Frontend-blue) ![Express](https://img.shields.io/badge/Express-Backend-black) ![Google AI](https://img.shields.io/badge/Google%20GenAI-Powered-yellow)

## 📌 Overview
**DEBUG** is an AI-powered code reviewer that allows developers to input code and receive insightful feedback. The system comprises a **React-based frontend** and an **Express.js backend** integrated with Google's Generative AI for code analysis.

## ✨ Features
- 📝 **Real-time Code Editing**: Uses `react-simple-code-editor` for a smooth editing experience.
- 🎨 **Syntax Highlighting**: Utilizes `prismjs` and `rehype-highlight` for clear code formatting.
- 🤖 **AI-Powered Review**: The backend leverages Google's Generative AI to analyze code quality.
- 📜 **Markdown Rendering**: Displays AI feedback in a formatted manner using `react-markdown`.
- ☁️ **Hosted on Render**: The app may take a few seconds to load initially due to Render's cold start.

---

## 🛠 Tech Stack
### **Frontend (React + Vite)**
![React](https://img.shields.io/badge/React-19.0.0-blue) ![Vite](https://img.shields.io/badge/Vite-6.2.0-purple)
- ⚛️ `react` - UI framework
- ⚡ `vite` - Build tool
- 📝 `react-simple-code-editor` - Lightweight code editor
- 🎨 `prismjs` - Syntax highlighting
- 📜 `react-markdown` - Markdown support
- 🔗 `axios` - API requests

### **Backend (Node.js + Express.js)**
![Node.js](https://img.shields.io/badge/Node.js-18-green) ![Express](https://img.shields.io/badge/Express-4.21.2-black)
- 🌐 `express` - Server framework
- 🤖 `@google/genai` - Google AI integration
- 🌍 `cors` - Cross-origin requests handling
- 🔒 `dotenv` - Environment variable management
- 🔄 `nodemon` - Development server monitoring

---

## 🚀 Installation & Setup
### **Prerequisites**
Ensure you have **Node.js** and **npm** installed.

### **Backend Setup**
```sh
cd backend
npm install
node server.js
```

### **Frontend Setup**
```sh
cd frontend
npm install
npm run dev
```

---

## 📌 Usage
1. Open the frontend in your browser (`http://localhost:5173` if using Vite).
2. Enter your JavaScript code in the editor.
3. Click **Review** to send the code to the AI for analysis.
4. AI-generated feedback will be displayed in the markdown preview section.

---

## 🌍 Deployment
The application is hosted on **Render**. Expect a slight delay in response due to cold starts.

### **Deploying Backend to Render**
1. Create a new **Render Web Service**.
2. Connect your GitHub repository.
3. Add environment variables (`.env` file) if required.
4. Deploy the backend service.

### **Deploying Frontend to Vercel**
1. Install Vercel CLI: `npm install -g vercel`
2. Run `vercel` in the `frontend` directory and follow the setup.
3. Deploy using `vercel --prod`.

---

## 🔮 Future Enhancements
- 🚀 Support for multiple programming languages.
- 🎯 Improved AI feedback with additional context.
- 🔐 User authentication for personalized code reviews.
- 💾 Saving and exporting review history.

---

## 👥 Contributors
- **Your Name** (Maintainer)
- Open for contributions! Feel free to fork and submit PRs.

---

## 📜 License
This project is licensed under the **MIT License**.

