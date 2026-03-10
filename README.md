# 📔 Personal Diary Web Application

A sleek, minimalistic, and user-friendly web application to maintain your personal diary entries. Built with a **Vanilla JavaScript** frontend and a **Node.js/Express/MongoDB** backend, this application offers an intuitive interface to log your thoughts, track your moods, and easily search past entries.

## ✨ Features

- **Dashboard Overview**: View total entries, entries for the current month, and your most common mood at a glance.
- **Create Entries**: Write your thoughts, give them a title, and associate a mood (Happy, Sad, Excited, Calm, Angry) with each entry.
- **Calendar View**: Navigate through an interactive calendar to read entries from specific days.
- **Search & Filter**: Powerful search capabilities to find past thoughts by keyword, date range, or mood.
- **Responsive Design**: A clean, sidebar-based navigation layout that works seamlessly across devices.

## 🛠️ Tech Stack

### Frontend
- **HTML5 & CSS3**: Structured layout with modern styling and responsive design.
- **Vanilla JavaScript**: Dynamic interactions, DOM manipulation, and state management without heavy frameworks.

### Backend
- **Node.js & Express.js**: RESTful API server.
- **MongoDB Atlas & Mongoose**: Cloud database integration for reliable data storage.
- **CORS & Body Parser**: Middleware for cross-origin requests and JSON parsing.

## 📁 Project Structure

```text
Persnoal-Diary-Application/
├── index.html          # Main HTML structure and UI
├── styles.css          # Application styling
├── diary.js            # Frontend logic and interactions
├── server.js           # Express backend server setup
├── package.json        # Node.js dependencies and scripts
└── package-lock.json   # Dependency lockfile
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- A [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account (or a local MongoDB instance).

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Har-dik25/Persnoal-Diary-Application.git
   cd Persnoal-Diary-Application
   ```

2. **Install backend dependencies:**
   ```bash
   npm install
   ```

3. **Configure Database Connection:**
   Open `server.js` and replace the `MONGODB_URI` placeholder with your actual MongoDB connection string:
   ```javascript
   const MONGODB_URI = "mongodb+srv://<username>:<password>@cluster0.mongodb.net/diary?retryWrites=true&w=majority";
   ```

4. **Start the Development Server:**
   ```bash
   npm run dev
   # OR
   npm start
   ```
   The backend server will run on `http://localhost:5000`.

5. **Open the Frontend:**
   You can open `index.html` directly in your browser or serve it using a local static server like Live Server in VS Code.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Har-dik25/Persnoal-Diary-Application/issues) if you have any suggestions.

---
*Happy coding!*
