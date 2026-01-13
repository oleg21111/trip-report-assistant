# Trip Report Assistant: Automated Trip and Fuel Expense Tracking in Telegram

Trip Report Assistant is an automated system for tracking business trips and fuel expenses, built in `Make` with a Telegram interface.

It transforms a standard chatbot into a practical financial tracking tool for department managers, drivers, and staff responsible for calculating vehicle compensation. The system allows for trip logging, automatic fuel cost calculation, monthly/yearly report generation, and centralized data storage without manual work.

---

## 💬 Core Idea

The goal is to simplify trip and compensation tracking as much as possible. A driver or employee submits trip data via a Telegram bot using a clear template, and the system automatically:
-   Validates the data for correctness.
-   Calculates fuel expenses.
-   Stores the information in a database.
-   Generates ready-to-use reports for managers or accountants.

No more Excel files in chats, no formula errors, and no manual calculations.

---

## ⚙️ Key Features

#### 🚗 1. Trip Logging via Telegram
✔️ Trip submission via bot commands for different drivers.
✔️ Unified input template: date, vehicle, route, purpose, mileage.
✔️ Automatic calculation of fuel cost and compensation amount.
✔️ Records are tied to a specific user via their Telegram User ID.

#### 📊 2. Centralized Database
✔️ All data is automatically stored and structured in Google Sheets.
✔️ A single, central database for all employees, minimizing human error.

#### 📅 3. Monthly and Yearly Reporting
✔️ A dedicated report sheet with filters for month and year.
✔️ Automatic generation of trip lists for the selected period.
✔️ Total expense calculation, ready for compensation and internal audits.

#### 🗑️ 4. Record Management
✔️ Securely delete the last submitted record for a specific user.
✔️ Safeguards against accidental deletion.
✔️ Clear system confirmation messages for all actions.

---

## 🧩 Tech Architecture

-   **Automation Platform:** `Make`
-   **User Interface:** `Telegram Bot API`
-   **Database & Reporting:** `Google Sheets`
-   **Real-time Updates:** `Webhook Handlers`
-   **Data Parsing:** `Regex`

---

## 💼 Business Impact

-  ✅ **Full control** over business trip expenses.
-  ⚡️ **Fast data entry** — less than 1 minute per trip.
-  📉 **Fewer errors** in calculations and reports.
-  📊 **A transparent system** for employee compensation.
-  🧠 **Centralized data storage** without spreadsheet chaos.
