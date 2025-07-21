
# 🌍 Travel and Expense Management System

A complete Travel and Expense Management System built using **HTML**, **CSS**, **JavaScript**, and **MongoDB**, designed to help users manage their travel plans, track expenses, and generate reports with ease. The system is responsive, user-friendly, and packed with essential features.

---

## 🚀 Features

- 🔐 **Authentication**: User Login / Signup with session handling
- 🙋 **User Profile**: View user details and overall travel expense stats
- 🧳 **Trip Management**:
  - Create trips with name, date, and budget
  - Edit or delete trips
  - Live search for trips
  - Sort/filter trips by name or date
- 💸 **Expense Tracking**:
  - Add, edit, or delete expenses (title, amount, date, category)
  - Filter expenses by category
  - View trip summary: Total expense vs budget
  - Expense percentage of total budget
  - Show pie chart of expenses by category (using Chart.js or Canvas API)
- 📄 **Reports**:
  - Download user profile summary as PDF
  - Download trip-wise reports as PDF
  - Print option for reports
- 🎨 **UI & UX**:
  - Fully responsive (mobile/tablet/desktop)
  - Dark/Light theme toggle
  - Alerts and validations for empty fields or errors

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Database**: MongoDB
- **Charting**: Chart.js / Canvas API
- **PDF Generation**: jsPDF or html2pdf.js
- **State Management**: LocalStorage or SessionStorage (for logout/reset session)

---

## 📸 Screenshots

> Include UI screenshots here (Login Page, Dashboard, Expense Pie Chart, etc.)

---

## 📁 Project Structure
project/
│
├── index.html
├── login.html
├── signup.html
├── dashboard.html
├── profile.html
├── styles/
│ └── main.css
├── scripts/
│ └── app.js
├── assets/
│ └── icons, images, charts
├── utils/
│ └── pdfGenerator.js, chartHandler.js
└── README.md

---

## 📝 How to Use

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/travel-expense-manager.git
   cd travel-expense-manager
Run MongoDB and ensure it is connected properly.

Serve the project locally using a live server or any static server. Example:
npm install -g live-server
live-server

