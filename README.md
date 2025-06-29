# 📊 Budget Tracker App – Task 4

This is **Task 4** of my App Development Internship project. In this task, I implemented **local data persistence** using **Room Database** in a Budget Tracker App built with **Kotlin** and **Jetpack Compose**.

---

## 📌 Task Summary

- Integrated **Room Database (SQLite)** for local data storage
- Created:
  - `TransactionEntity` (data model)
  - `TransactionDao` (Data Access Object)
  - `AppDatabase` (Room database class)
  - `DatabaseProvider` (singleton helper for context-based DB access)
- Used `collectAsState()` to dynamically observe and display stored data
- Built a polished UI with Compose including:
  - Home screen
  - Add Transaction screen
  - Transaction List screen

---

## 📁 Folder Structure

