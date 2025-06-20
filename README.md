
# 🏆 LeaderBoard Frontend – Angel-Thon 5.0

The **LeaderBoard Frontend** is a dynamic and interactive web interface developed to track and display participant rankings in real-time during Angel-Thon 5.0. It provides an engaging user experience with a responsive layout, seamless updates, and integration with backend services powered by Google Apps Script or RESTful APIs.

This frontend was designed to enhance visibility, encourage competition, and ensure transparency during the event. It is lightweight, scalable, and easy to deploy across platforms.

---

## 📌 Overview

Angel-Thon 5.0 is a coding and innovation challenge, and the leaderboard application serves as the real-time scoreboard that showcases participant progress, rank, and scores. The frontend offers features such as:

- Live updates of scores
- Sorted and ranked view of participants
- Responsive interface for desktop and mobile
- Easy integration with backend data sources

---

## 🚀 Features

- 🥇 **Real-Time Rankings**: Dynamically updates user scores from the backend.
- 📱 **Responsive UI**: Works seamlessly across all device sizes.
- 🎯 **Participant Filtering**: Easily search or filter participants.
- ⚡ **Efficient State Handling**: Keeps UI snappy with optimized rendering.
- 🧪 **Tested & Modular Codebase**: Components are cleanly structured for readability and maintenance.

---

## 🧰 Tech Stack

- **React.js** – JavaScript library for building user interfaces
- **Redux (optional)** – For global state management
- **HTML/CSS** – Page layout and styling
- **JavaScript (ES6)** – Application logic
- **Axios / Fetch API** – For REST API integration
- **Google Apps Script** – Used on backend (for this version)

---

## 📁 Project Structure

```
LeaderBoard-Frontend/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── LeaderTable.js
│   │   └── Loader.js
│   ├── App.js
│   ├── index.js
│   └── styles/
│       └── main.css
│
├── .env
├── package.json
└── README.md
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/PrabhavNasa/LeaderBoard-Fronted.git
cd LeaderBoard-Fronted
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment (if needed)

If you're using an API:

```env
REACT_APP_API_URL=https://your-api-url.com
```

### 4. Run the Application

```bash
npm start
```

The app will be available at `http://localhost:3000`.

---

## 📊 Live Demo

> _[Add demo link if deployed on Netlify, Vercel, or GitHub Pages]_

---

## 🔌 Backend Integration

This frontend is designed to consume a leaderboard API, either served from:
- A custom Node.js backend
- Google Apps Script-based backend pulling from Google Sheets

Sample API expected:

```json
[
  {
    "name": "Alice",
    "score": 340,
    "rank": 1
  },
  {
    "name": "Bob",
    "score": 270,
    "rank": 2
  }
]
```

---

## 📈 Future Enhancements

- Add animations for rank changes
- Export to CSV/PDF
- Admin login for score entry
- Support multiple leaderboards by event
- Graphical charts for performance trends

---

## 🧠 Why This Project?

Hackathons and coding competitions thrive on energy and visibility. This leaderboard helps organizers and participants track standings live, motivating teams and ensuring fair competition. It also reflects real-world frontend skills like API integration, responsive design, and live data handling.

---

## 👨‍💻 Author

**Prabhav Nasa**  
GitHub: [@PrabhavNasa](https://github.com/PrabhavNasa)  
LinkedIn: [prabhavnasa23](https://linkedin.com/in/prabhavnasa23)

---

## 📄 License

This project is licensed under the **MIT License**.

---

Made with 💡 to support innovation at Angel-Thon 5.0.
