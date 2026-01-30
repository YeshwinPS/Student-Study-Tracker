📚 Student Study Tracker & Stress Monitor

📝 Project Description

Student Study Tracker & Stress Monitor is a Java–MySQL desktop application that helps students track their daily study hours and stress levels. The system stores data in a MySQL database using JDBC and helps analyze study habits to promote better academic planning and mental well-being.

---

🎯 Features

* Add student details (name, semester)
* Log daily study hours
* Record stress levels (1–5)
* Store data securely in MySQL
* Simple and beginner-friendly Java structure
* Uses JDBC for database connectivity

---

🛠️ Technologies Used

* **Java** (Core Java)
* **JDBC** (MySQL Connector/J)
* **MySQL**
* **Eclipse IDE**

---

🗂️ Project Structure

```
StudentStudyTracker
│
├── DBConnection.java
├── AddStudent.java
├── AddStudyLog.java
├── MainApp.java
└── MySQL Scripts
```

---

🗄️ Database Structure

**Database Name:** `study_tracker`

Tables:

* `students`
* `study_log`

The database stores student information and their daily study logs with stress levels.

---

▶️ How to Run the Project

1. Install **MySQL** and start the MySQL server
2. Create the database and tables using the provided SQL scripts
3. Open the project in **Eclipse IDE**
4. Add **MySQL Connector/J** to the project build path
5. Update database credentials in `DBConnection.java`
6. Run `MainApp.java`

---

✅ Sample Output

```
Database connected!
Student added!
Study log added!
Data inserted successfully
```

---

📌 Use Case

This project is useful for students who want to:

* Monitor study consistency
* Understand stress patterns
* Improve academic productivity

---

🚀 Future Enhancements

* Swing/JavaFX UI
* Weekly and monthly reports
* Stress-level alerts
* Login system
* Data visualization charts

---

👩‍💻 Author
Yeshwin PS

---

