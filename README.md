# 🏦 Banking Data Management and Analysis System

## 📘 Overview
This project focuses on developing a relational banking database system that efficiently manages and analyzes customer, account, and transaction data.  
It simulates real-world banking operations and uses **SQL** and **Python** to perform data-driven analysis, such as calculating average balances, identifying active accounts, and summarizing transactions.

---

## 🧾 Database Structure
The database is designed with multiple interconnected tables representing key banking entities and their relationships.

### **Tables Used**
- 👤 **Customer_Information:** Stores customer details such as ID, name, address, and state code.  
- 🧮 **Customer_InfoExport:** Contains account types, balances, and account status.  
- 💳 **Account_Data:** Records customer transactions with date, amount, and transaction channel.  
- 🔗 **Account_Mapping:** Links customers’ primary and secondary accounts.  
- 📊 **Transaction_Log:** Maintains account creation details and performance data.  
- 📁 **Customer_Alerts:** Handles exporting summarized customer data.  
- 🧠 **Interest_Info:** Defines relationships between linked or joint accounts.

---

## 🧠 Project Workflow
1️⃣ **Database Design:** Created normalized tables and defined primary–foreign key relationships.  
2️⃣ **Data Insertion:** Automated record entry using Python and the `sqlite3` library.  
3️⃣ **Data Retrieval:** Used SQL `SELECT`, `WHERE`, `JOIN`, and `GROUP BY` clauses to query data.  
4️⃣ **Data Analysis:** Generated insights such as average balances per customer, inactive accounts, and total transactions.  
5️⃣ **Visualization:** Displayed results using **Pandas DataFrames** and **Tabulate** for readable outputs.

---

## ⚙️ Tech Stack
- 🐍 **Programming Language:** Python  
- 🗃️ **Database:** SQLite (`sqlite3` library)  
- 📚 **Libraries:** Pandas, Tabulate, OS  
- 💻 **Tools:** Google Colab, SQL, DataFrames  

---

## 📈 Results
✅ Efficient management and analysis of customer–account–transaction relationships.  
✅ Simplified SQL operations through Python automation.  
✅ Derived insights such as linked account reports and average balance analysis to assist banking decision-making.

---

## 💡 Key Features
✨ Automated data creation, retrieval, and reporting using Python functions.  
✨ Real-time insights via SQL aggregate and join queries.  
✨ Structured data visualization using Pandas and Tabulate.  
✨ Database securely stored and accessible through Google Drive for persistence.

---
  
**Tools Used:** Python, SQLite, Pandas, Google Colab  


