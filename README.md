# TaskFlow 🧠 ✅

**TaskFlow** is a modern, responsive, and elegant task management web app that allows users to organize tasks by priority, due date, and filter them efficiently. It uses **Firebase**  as a backend Database for secure authentication and real-time database updates.

> ✨ Flow through your tasks with ease.

---
## 🔗 Live Demo

🌐 [taskflow-ayush.netlify.app](https://taskflow-2025.netlify.app/)

## 🚀 Features

- ✅ Add tasks with priorities (High, Medium, Low)
- 🗓 Set due dates to stay on schedule
- 🔍 Filter tasks by priority
- ✏️ Edit and delete tasks easily
- 🔒 User authentication using:
  - Email/Password
  - Google Sign-In
- ☁️ Real-time sync with **Firestore**
- 🌐 Fully responsive and mobile-friendly
- 🎨 Stunning particle animation background with glassmorphism design

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript, TailwindCSS
- **Backend**: Firebase Auth, Firebase Firestore
- **Hosting**: Netlify (Optional deployment)

---

## 🔐 Authentication Options

| Method          | Description                         |
|-----------------|-------------------------------------|
| Anonymous       | Quick access, temporary             |
| Email/Password  | Persistent user ID and login        |
| Google Sign-In  | Fast login with Google account      |

---

## 🧾 Folder Structure

```
My-TaskFlow-App/
├── index.html
├── style.css (optional)
├── script.js (optional)
└── README.md
```

---

## 📦 Getting Started

### 🔧 Prerequisites
- A Firebase project
- Firebase Authentication (Google & Email/Password) enabled
- Firestore Database in **test mode** or with proper security rules

### ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/my-taskflow-app.git
   cd my-taskflow-app
   ```

2. Add your Firebase config in `index.html`:
   ```js
   const firebaseConfig = {
     apiKey: "...",
     authDomain: "...",
     projectId: "...",
     ...
   };
   ```

3. Enable Authentication in Firebase Console
   - Email/Password
   - Google

4. Deploy locally:
   ```bash
   Live Server (VS Code) or open `index.html` in browser
   ```

5. Deploy to Netlify:
   - Go to [https://app.netlify.com/](https://app.netlify.com/)
   - Drag and drop your project folder or connect GitHub

---


