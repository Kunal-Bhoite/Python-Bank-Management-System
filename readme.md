# 🏦 Streamlit Bank App

A simple **Bank Management System** built using **Streamlit** and Python.  
This app allows users to **create accounts, deposit/withdraw money, update account information, and delete accounts** through an interactive web interface.  
All data is stored securely in a **JSON file (`data.json`)**.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ➕ Create Account | Register a new account (age 18+, 4-digit PIN) |
| 💰 Deposit | Add money to an account (max 10,000 per transaction) |
| 💸 Withdraw | Withdraw money with sufficient balance |
| 👤 Show Details | View account info using Account Number & PIN |
| ✏ Update Info | Update name, email, or PIN |
| 🗑 Delete Account | Permanently delete an account |
| 🔐 Security | All transactions require PIN validation |

---

## 🧱 Tech Stack

- **Python 3.12PYTHON**  
- **Streamlit** (for web UI)  
- **File-based storage** using `data.json`  
- **Backend Logic** implemented in `hello.py` (Bank class)

---

## 📁 Project Structure
📂 BANK-MANAGEMENT-MAIN
│
├── app.py # Main Streamlit interface
├── hello.py # Bank class (CRUD operations)
├── data.json # Auto-created database file
└── README.md # Project documentation

