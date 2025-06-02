# 💰 Wallet Web Application

A full-stack Wallet Management Web Application that allows users to manage transactions securely and efficiently. Built with **Spring Boot** for the backend and **React JS** for the frontend, this application supports user authentication, transaction history, and detailed tracking.

---

## 🚀 Features

- 🔐 User Registration & Login (Session-based)
- ➕ Add Income and Expense Transactions
- 📜 View Transaction History
- 🗂️ Filter Transactions by Date and Type
- 📊 Transaction Summary and Dashboard (coming soon)
- ❌ Remove invalid or incomplete transactions
- ✅ Admin-only song access logic (custom implementation)
- 📁 Separate user-specific playlist and data management (custom logic)

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- HTML5, CSS3, JavaScript
- Axios
- GSAP (Optional for Animations)

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

```bash
cd spring-backend

### Open application.properties and configure your database:

- spring.datasource.url=jdbc:mysql://localhost:3306/wallet_db
- spring.datasource.username=your_username
- spring.datasource.password=your_password

### Install dependencies and run:

mvn clean install
mvn spring-boot:run

### 💻 Frontend (React)
- cd react-frontend
  - Install dependencies:
    - npm install
    - npm run dev

### 📂 Folder Structure
- /project-root
  ├── react-frontend/           # React Frontend Code
  ├── spring-backend/           # Spring Boot Backend Code
  ├── testing-documents/        # Excel and Manual Testing Docs
  └── README.md

### 🧪 Testing
- Testing documents are available in the /testing-documents/ folder, including:

✔️ Pre-requisites

✔️ Test Scenarios & Cases

✔️ Expected vs Actual Result

✔️ Status (Pass/Fail)

📸 Images can be added for verification


🧑‍💻 Developed by
Prasann Malanaik
Sankeshwar, Belagavi, Karnataka, India
📧 prasannmalanaik@gmail.com
📱 +91 8861116581
