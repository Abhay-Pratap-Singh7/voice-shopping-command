# 🛒 Voice Shopping Assistant

A **voice-powered shopping list manager** built with **React + Firebase + TailwindCSS**, enabling users to manage shopping lists using **natural voice commands**.  
It also provides **smart suggestions**, **item history**, and **real-time updates** — making shopping more interactive and efficient.

---

## 🚀 Features

- 🎙️ **Voice Commands**  
  Manage items with your voice:
  - `Add 2 milk`
  - `Remove bread`
  - `Change rice price to 50`
  - `Find Amul under 200`
  - `Refresh suggestions`

- 📦 **Shopping List Management**  
  - Add items with **quantity, brand, category, and price**  
  - Mark items as **bought** or remove them  
  - Real-time sync with Firebase  

- 💡 **Smart Suggestions**  
  Suggests frequently added or recently bought items.

- 🔍 **Search & Filters**  
  - Search by name, brand, category, or price range.  
  - Example: *Find snacks under 100*.

- 🗣️ **Voice + Visual Feedback**  
  - System **speaks back** confirmations & errors  
  - UI shows **alerts** (Success, Error, Info, Warning)

- 🎨 **Modern UI**  
  - Built with **TailwindCSS**  
  - Smooth animations, gradients, and attractive cards.

---

## 🛠️ Tech Stack

- **Frontend:** React (Vite), TailwindCSS  
- **Backend:** Firebase Firestore + Firebase Authentication  
- **Voice Engine:** Web Speech API  
- **Deployment:** Netlify / Vercel / Firebase Hosting  

---

## 📂 Project Structure

```
voice-shopping-assistant/
│── public/           # Static files (favicon, index.html)
│── src/
│   ├── components/   # UI Components (ShoppingList, Suggestions, VoiceInput)
│   ├── utils/        # Command parser, history, speech utils
│   ├── App.jsx       # Main App component
│   ├── firebase.js   # Firebase config & initialization
│   └── index.css     # Tailwind & custom styles
│── .gitignore        # Ignored files (node_modules, build, logs)
│── package.json      # Dependencies & scripts
│── README.md         # Documentation
```

---
