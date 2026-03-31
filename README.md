# 🧾 Expense Tracker - Java Project

## 👤 Student Details

* **Name:** Sakshi Narkhede
* **Roll No:** 24BHI10014

---

## 💻 Project Description

This is a simple **Expense Tracker application** developed in Java.
It allows users to:

* Add expenses
* View all expenses
* Calculate total spending
* Search expenses by category

All data is stored in a text file (`expenses.txt`).

---

## 📁 Project Files

### 🔹 File 1: `Expense.java`

* Defines the **Expense class**
* Contains:

  * Title
  * Amount
  * Category
* Converts object data into string format for file storage

---

### 🔹 File 2: `ExpenseManager.java`

Handles all operations related to expenses:

* Add Expense (stores data in file)
* View Expenses (reads from file)
* Total Expense (calculates sum)
* Search by Category

---

### 🔹 File 3: `Main.java`

* Entry point of the program
* Provides menu-driven interface
* Takes user input and calls appropriate functions

---

### 🔹 File 4: `expenses.txt`

* Stores all expense records
* Format:

```
Title,Amount,Category
Food,200,Lunch
Travel,500,Bus
```

---

## ⚙️ Features

* 📌 File handling using Java
* 📌 Menu-driven program
* 📌 Data stored persistently in text file
* 📌 Simple and user-friendly

---

## ▶️ How to Run

### Step 1: Compile all files

```bash
javac *.java
```

### Step 2: Run the program

```bash
java Main
```

---


