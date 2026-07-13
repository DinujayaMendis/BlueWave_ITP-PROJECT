# BlueWave Project 🌊

Welcome to the **BlueWave** project! This is a complete Web Application divided into three main components. This guide is written in a simple way so that anyone,  can understand how the project works and how to run it.

---

## 🏗 Main Components

The project is structured into 3 main folders:
1. **Frontend** (The Customer/User Interface)
2. **Admin** (The Management Dashboard)
3. **Backend** (The Server & Database Connection)

---

### 1. Frontend - User Interface 💻
This is the part of the website that regular customers and users see when they visit.
* **Technologies Used:** React (for building the pages), Tailwind CSS (for styling and design), Redux (for managing state and data).
* **Key Features:**
  * Interactive Maps (using Leaflet).
  * Ability to download information as PDF reports.
* **How to run this part:** 
  Open a terminal, go to the folder by typing `cd frontend`, run `npm install` to get the dependencies, and then run `npm start`.

### 2. Admin - Management Dashboard 📊
This section is strictly for the staff or website owners. It allows them to add new information, manage existing data, delete records, and monitor activities.
* **Technologies Used:** React, Tailwind CSS, Redux. (It communicates with the Backend using a proxy on Port 5000).
* **Key Features:**
  * Clear data visualization using Charts and Graphs (using Chart.js).
  * Report generation and PDF downloads.
* **How to run this part:** 
  Open a terminal, go to the folder by typing `cd admin`, run `npm install` to get the dependencies, and then run `npm start`.

### 3. Backend - Server & Database ⚙️
Even though we don't see this part directly on the screen, it is the engine that powers the whole system. It securely stores user data (like passwords and records) in the database, handles image uploads, and sends the requested data to the Frontend and Admin panels.
* **Technologies Used:** Node.js, Express.js (to create the server), MongoDB / Mongoose (for database storage), and Multer (for handling file/image uploads).
* **How to run this part:** 
  Open a terminal, go to the folder by typing `cd backend`, run `npm install` to get the dependencies, and then run `npm run dev`.

---

## 🚀 Quick Start Guide (How to run the entire project)

To run this project on your computer, you must have **Node.js** installed.

Open your code editor (like VS Code) and open **3 separate terminal windows**. Follow these steps in each terminal:

**Step 1: Start the Backend (Terminal 1)**
```bash
cd backend
npm install
npm run dev
```

**Step 2: Start the Frontend (Terminal 2)**
```bash
cd frontend
npm install
npm start
```

**Step 3: Start the Admin Panel (Terminal 3)**
```bash
cd admin
npm install
npm start
```

*Once all three are running, your browser will automatically open the Frontend website and the Admin dashboard!*
