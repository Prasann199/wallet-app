# 💰 Wallet Web Application

A full-stack Wallet Management Web Application that allows users to manage transactions securely and efficiently. Built with **Spring Boot** for the backend and **React JS** for the frontend, this application supports user authentication, transaction history, and detailed tracking.

---

## 🚀 Features

- 🔐 User Registration & Login (Session-based)
- ➕ Add Money and remove money
- 📜 View Transaction History

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- tailwind css(Library)
- Axios

**Backend:**
- Spring Boot
- Java
- Spring Security (for session handling)
- MySQL (or any relational DB)
- Hibernate/JPA
- Maven

**Testing & Documentation:**
- Excel Sheets for Test Cases
- Manual Testing with Expected & Actual Results
- Screenshot proof support in documentation

---

## ⚙️ Installation & Setup

### 📦 Prerequisites

- Node.js (v14 or above)
- Java JDK (v17+ recommended)
- Maven
- MySQL Server
- Git

---

### 🔧 Backend (Spring Boot)


### ✏️ Configure `application.properties`

Update your database credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/wallet_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 📦 Install & Run

```bash
mvn clean install
mvn spring-boot:run
```

---

## 💻 Frontend Setup (React)

### 🛠 Requirements

- Node.js & npm

### 📁 Navigate to Frontend

```bash
cd react-frontend
```

### 📦 Install Dependencies

```bash
npm install
```

### ▶️ Run the Development Server

```bash
npm run dev
```

---

## 📁 Folder Structure

```
/project-root
├── frontend -> wallet/         # React Frontend Code
├── debit-credit-wallet/         # Spring Boot Backend Code
├── testing-documents/      # Excel and Manual Testing Docs
└── README.md               # Project Overview and Setup
```

---

## 🧪 Testing Documentation

Manual testing documentation is available in the `/testing-documents/` folder, containing:

- ✅ Pre-requisites  
- 🧪 Test Scenarios & Test Cases  
- 📌 Steps to Reproduce  
- 🎯 Expected vs Actual Results  
- 📊 Status (Pass/Fail)  
- 📸 Screenshot placeholders for proof

---

## 👨‍💻 Developed By

**Prasann Malanaik**  
📍 Sankeshwar, Belagavi, Karnataka, India  
📧 prasannmalanaik@gmail.com  
📱 +91 8861116581  

---
