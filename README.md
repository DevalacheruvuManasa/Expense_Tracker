# 💰 Expense Tracker Application

A full-stack Expense Tracker application built with **React.js**, **Spring Boot**, and **MySQL** to help users track, manage, and visualize their daily expenses.

---

## 🛠️ Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | React.js, HTML, CSS, Bootstrap |
| Backend      | Java, Spring Boot (REST APIs) |
| Database     | MySQL              |
| Tools Used   | Postman, Git, GitHub |

---

## 🔥 Features

- Add, update, and delete expenses
- Categorize expenses
- View total expenses
- Date-wise filtering
- RESTful API integration
- Responsive user interface

---

## 🧩 Project Structure

```bash
Expense-Tracker/
│
├── backend/                     # Spring Boot Application
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/expensetracker/
│   │   │   │   ├── controller/
│   │   │   │   ├── model/
│   │   │   │   ├── repository/
│   │   │   │   ├── service/
│   │   │   │   └── ExpenseTrackerApplication.java
│   │   │   └── resources/
│   │   │       ├── application.properties
│
├── frontend/                    # React.js Frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   └── package.json
│
└── README.md
