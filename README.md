# 💰 Fee Management System

## 📌 Project Description

Fee Management System ek **Java-based desktop application** hai jo schools aur colleges ke liye design kiya gaya hai.
Is system ki help se admin students ki fees ko easily manage kar sakta hai — jaise ki add, update, view aur track payments.

---

## 🚀 Features

### 🔐 Login System

* Secure admin login
* Username & password authentication

### 👨‍🎓 Student Management

* Add new student details
* Update student information
* Delete student records
* View all students in table format

### 💵 Fee Management

* Student-wise fee entry
* Track paid & pending fees
* Fee status (Paid / Pending)

### 🔍 Search System

* Search student by name or ID
* Fast data retrieval

### 📊 Reports

* Total fee collected
* Pending fee details
* Student-wise report

### 🎨 User Interface

* Simple and user-friendly UI
* Java Swing forms
* JTable for data display

---

## 🛠️ Technologies Used

* **Frontend:** Java Swing
* **Backend:** Java (JDBC)
* **Database:** MySQL
* **IDE:** NetBeans / Eclipse
* **Connector:** MySQL Connector/J

---

## 🗄️ Database Tables

### 1. Admin Table

* id (Primary Key)
* username
* password

### 2. Students Table

* id (Primary Key)
* name
* course
* contact

### 3. Fees Table

* id (Primary Key)
* student_id (Foreign Key)
* amount
* status (Paid / Pending)
* date

---

## ⚙️ Installation & Setup

### Step 1: Clone Project

```bash
git clone https://github.com/your-username/fee-management-system.git
```

### Step 2: Setup MySQL Database

* Create database: `fee_db`
* Create tables (admin, students, fees)

### Step 3: Configure Database Connection

```java
jdbc:mysql://localhost:3306/fee_db
username: root
password: root
```

### Step 4: Add MySQL Connector

* Add `mysql-connector-j-8.x.x.jar` to project libraries

### Step 5: Run Project

* Run `Login.java`

---

## 🔑 Default Login

Username: admin
Password: admin123

---

## 📸 Screenshots (Optional)

* Login Page
* Dashboard
* Student Form
* Fee Form
* Reports

---

## 🔥 Future Enhancements

* 🧾 PDF fee receipt
* 📊 Charts & analytics
* 🔐 Role-based login (Admin/Staff)
* 🌐 Web-based version

---

## 🧠 Learning Outcomes

* Java Swing GUI design
* JDBC connectivity
* CRUD operations
* Database management
* Real-world project building

---

## 👨‍💻 Author

RUBY SINGH
Java Developer🚀

---

## ⭐ Conclusion

Fee Management System ek **efficient aur user-friendly solution** hai jo fee tracking ko easy banata hai.
Ye project beginners ke liye best hai full stack concepts samajhne ke liye.

---

✨ *Made with Java & Dedication* ✨
