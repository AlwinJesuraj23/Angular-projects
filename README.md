# 📋 Task Management Application

**Training Project 1**

## 📌 Project Overview

The **Task Management Application** is a training-based single-page web application built using **AngularJS and TypeScript**.
It allows users to efficiently **manage tasks** by creating, updating, deleting, and filtering them.
This project focuses on understanding **frontend architecture, data handling, form validation, and UI design**, without using a backend server.

All task data is stored using **in-memory JSON / local JSON**, making it ideal for learning and demonstration purposes.

---

## 🎯 Project Purpose

* Practice **AngularJS fundamentals**
* Work with **TypeScript-based components**
* Implement **CRUD operations**
* Learn **form validation**
* Understand **data filtering and UI state management**
* Build a real-world styled task management system

---

## 🚀 Features

### ✅ Task Management

* View all tasks in a structured table
* Add new tasks
* Edit existing tasks
* Delete tasks (soft delete using `IsDeleted` flag)

### 🔍 Task Filtering

* Filter tasks by:

  * **Task Name**
  * **Task Type** (Front End / Back End)
  * **Task Category** (High / Medium / Low)

### 🧾 Form Validation

* Mandatory field validation
* Error messages displayed when required fields are missing
* Prevents invalid task submissions

### 📊 Task List Table

* Displays task data using a basic HTML table
* Columns included:

  * Task Name
  * Task Description
  * Task Type
  * Task Category
  * Active Status
  * Created Date
  * Modified Date
  * Actions (Edit / Delete)

> 🔧 *Future enhancement:* Replace basic table with a data table for pagination and sorting.

---

## 🧱 Task Data Structure (Columns)

| Column Name     | Description               |
| --------------- | ------------------------- |
| TaskName        | Name of the task          |
| TaskDescription | Detailed task description |
| TaskType        | Front End / Back End      |
| TaskCategory    | High / Medium / Low       |
| IsActive        | Task active status        |
| CreatedDate     | Task creation timestamp   |
| ModifiedDate    | Last updated timestamp    |
| IsDeleted       | Soft delete flag          |

---

## 🛠️ Technologies Used

### Frontend

* **AngularJS** – Framework for building single-page applications
* **TypeScript** – Strongly typed JavaScript for better code quality
* **HTML** – Structure and layout
* **CSS** – Styling and responsive UI

### Data Storage

* **In-memory JSON / Local JSON**
* No backend or database used

---

## 📂 Project Type

* **Training / Learning Project**
* No backend integration
* Suitable for beginners learning Angular and frontend development

---

## ▶️ How to Run the Project

1. Clone the repository

   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder

   ```bash
   cd task-management
   ```
3. Install dependencies

   ```bash
   npm install
   ```
4. Run the application

   ```bash
   ng serve
   ```
5. Open in browser:

   ```
   http://localhost:4200
   ```

---

## 📈 Future Enhancements

* Integrate backend API
* Use database instead of in-memory JSON
* Add pagination and sorting using data tables
* User authentication
* Role-based access control

---

## 🧑‍💻 Author

**Training Project – Task Management**
Built for learning and practice using AngularJS and TypeScript.

---

If you want, I can also:

* ✨ Shorten this README
* 📄 Add screenshots section
* 🏷️ Make it more **resume-friendly**
* 🧠 Rewrite it in **simple beginner-friendly language**

Just tell me 👍
