# School Management System

**School Management System** is a Python-based project designed to simplify student record handling, exam result processing, and automated report card generation.  
It uses **MySQL** for database management and **FPDF** for professional PDF creation.

---

## 📌 Features
- 🗂 **Student Record Management** – Add, update, delete, and search student profiles.
- 📊 **Exam & Result Processing** – Store and manage test scores for periodic and final exams.
- 📝 **PDF Report Card Generation** – Auto-generate professional report cards with logo using FPDF.
- 📧 **Email Integration** – Send report cards directly to students/parents.
- 🔗 **MySQL Integration** – Secure, fast, and reliable data storage.
- ⚡ **User-Friendly Interface** – Simple command-line based workflow.

---

## 🚀 Installation

1️⃣ **Clone or Download the Project**  
Place the project folder in your preferred directory.

2️⃣ **Install Required Libraries**  
```bash
pip install mysql-connector-python fpdf pillow
```

3️⃣ **Configure Database**  
Inside `main.py`, update your MySQL credentials:
```python
DB_HOST = "localhost"
DB_USER = "root"
DB_PASSWORD = "your_password"
DB_NAME = "school_db"
```

4️⃣ **Add Logo File**  
Place your `logo.jpeg` in the same folder as `main.py` (used in report card PDF).

5️⃣ **Run the Application**  
```bash
python main.py
```

---

## 📂 Project Structure
```
SchoolManagementSystem/
│-- main.py    # Main program file (all features)
│-- logo.jpeg  # Logo for report card
│-- README.md  # Project documentation
```

---

## 🛠 Technologies Used
- Python 3
- MySQL
- FPDF (PDF generation)
- Pillow (Image handling)
- smtplib (Email sending, built-in)

---

## 💡 Future Enhancements
- GUI interface using Tkinter
- Attendance management
- Timetable scheduling
- Web dashboard version

---


## 👨‍💻 Author

**Divyam Sethi**  
🔗 [LinkedIn](https://www.linkedin.com/in/divyam-sethi-3a5141232)  
📧 [Email](mailto:divyamsethi1804@gmail.com)

---

## ⭐️ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub and sharing it!