 BudgetWise – AI-Based Personal Finance Tracker

Intelligent Expense Tracking & Financial Insights Using AI

📌 Project Overview

BudgetWise is a personal finance tracking and budgeting application designed to help users manage their expenses, create budgets, track savings goals, and understand their spending habits. It provides a dashboard with financial summaries and charts to help users make better financial decisions.

The application uses a React.js frontend, Java Spring Boot backend, and MySQL database. It also includes an AI-based expense analysis feature to identify spending patterns and provide saving suggestions.

🎯 Objectives

Track and manage daily expenses and transactions.
Create budgets and monitor spending limits.
Set savings goals and track progress.
Display financial summaries through a dashboard.
Visualize expenses using charts and reports.
Provide AI-based expense analysis and saving suggestions.
Store and manage user information securely.

✨ Features

User Registration and Login: Create an account and log in.
Dashboard: View monthly expenses, budgets, remaining budget, and recent transactions.
Expense Management: Add, view, edit, and delete expenses.
Budget Management: Set category-wise budgets and monitor spending.
Savings Goals: Create savings targets and track progress.
Categories and Accounts: Organize financial records.
Reports and Charts: View monthly reports and graphical expense summaries.
Settings: Manage profile details, notification preferences, language, and account settings.

AI Expense Analysis: Analyze spending patterns and receive suggestions for saving money.

🛠️ Technologies Used

Technology
Purpose
React.js
Frontend development
Java
Backend programming
Spring Boot
REST API development
Spring Security and JWT
Authentication and API security, if enabled in the current version
MySQL
Database management
MySQL Workbench

Database inspection and validation

Apache Tomcat

Backend application runtime

Maven

Dependency management and build

Git and GitHub

Version control and project hosting

🏗️ System Architecture

User
  |
  v
React.js Frontend
  |
  v
Spring Boot REST APIs
  |
  v
Service and Business Logic
  |
  v
MySQL Database

The frontend communicates with the backend through REST APIs. The backend processes requests, applies business rules, and interacts with the MySQL database.

📂 Project Modules

Authentication – Registration and login.

Dashboard – Financial summaries and recent transactions.

Expenses and Transactions – Expense CRUD operations.

Budget Management – Category-wise budget tracking.

Savings Goals – Savings target and progress tracking.

Categories and Accounts – Financial record organization.

Reports and Charts – Expense reports and visualizations.

Settings – Profile and user preferences.

AI Expense Analysis – Spending insights and saving recommendations.

⚙️ Prerequisites

Install the following before running the project:

Java JDK 21

Node.js and npm

MySQL Server

MySQL Workbench (optional, for database management)

Maven

Git

🚀 Installation and Setup

1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY

Replace the repository URL with your actual GitHub repository URL.

2. Configure the MySQL Database

Start MySQL Server.

Create a database for the application.

Configure the database URL, username, and password in the Spring Boot application.properties file.

Example configuration:

spring.datasource.url=jdbc:mysql://localhost:3306/budgetwise
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD

Use your actual database name and local credentials. Do not commit real passwords or secret keys to GitHub.

3. Run the Backend

Open a terminal in the Spring Boot project directory and run:

mvn spring-boot:run

Make sure the database configuration and required application properties are set correctly before starting the backend.

4. Run the Frontend

Open another terminal in the React frontend directory and run:

npm install
npm start

If your project uses Vite, use the command specified in its package.json, commonly:

npm run dev

Open the local frontend URL shown in the terminal.

🧪 Testing

The project can be validated using:

Functional Testing: Verify registration, login, expenses, budgets, savings goals, settings, and reports.

API Testing: Test REST endpoints and validate request and response data using Postman.

Database Testing: Verify that records are inserted, updated, retrieved, and deleted correctly in MySQL.

Integration Testing: Check communication between React.js, Spring Boot, and MySQL.

Regression Testing: Verify that existing features continue to work after changes.

UI Testing: Check page layout, form validation, navigation, and browser compatibility.

🔒 Security Notes

Keep database credentials and JWT secrets outside publicly committed files.

Use environment variables or an untracked configuration file for sensitive values.

Validate user inputs on the backend.

Verify authentication and authorization settings before deploying the application.

Future Enhancements

Automated expense categorization using AI.

Export financial reports to PDF or Excel.

Recurring expense reminders.

Enhanced financial analytics and personalized insights.

Deployment to a cloud platform.

Project Information

Project Name: AI-Based BudgetWise Personal Finance Tracker
Project Type: Final Year Project
Domain: Personal Finance Management
Purpose: Expense tracking, budgeting, savings management, and AI-based financial insights.

📄 License

This project is intended for educational and learning purposes. Add a license file if you want to specify how others may use, modify, and distribute the code.
