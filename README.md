# 🏫 SchoolDesk – School Management System in Python

**SchoolDesk** is a desktop-based application that simplifies student record handling, exam result processing, and automated report card generation.  
It uses **MySQL** for database management and **FPDF** for generating professional PDF report cards, with optional email delivery.

---

## 📌 Project Summary

This project was developed to automate and simplify school administrative tasks such as managing student records, tracking fees, generating report cards, and sending them via email.  
**SchoolDesk** eliminates repetitive manual work and reduces the risk of human errors by integrating database operations with PDF automation.

---

## 💡 Problem Statement

Managing student records and generating report cards manually is time-consuming and error-prone. The goal was to create an application that could store all student details securely, manage fee records, generate report cards instantly, and even email them to parents — all from one place.

---

## 🔧 Features

- 🗂 **Student Record Management** – Add, update, delete, and search student profiles  
- 💰 **Fee Management** – Track paid and pending fees  
- 📊 **Exam & Result Processing** – Store marks for periodic and final exams  
- 📝 **PDF Report Card Generation** – Create professional report cards with school logo using **FPDF**  
- 📧 **Email Integration** – Send report cards directly to parents/students  
- 🔍 **Search Filters** – Find students by admission number or phone number  
- 🖥️ **CLI Menu** – Simple interactive menu-based navigation  

---

## 🧰 Tech Stack

- **Python 3.x**
- **MySQL** – Database management
- **FPDF** – PDF generation
- **Pillow (PIL)** – Logo/image handling
- **smtplib & email.mime** – Email sending (built-in Python)
- **Tkinter** – Optional GUI modules (not core to current version)

---

## 🚀 How It Works

1. On startup, the program connects to MySQL and ensures the `school` database and `student` table exist.
2. User chooses between:
   - Viewing school details
   - Managing student details
   - Generating reports
3. For student management:
   - Add new student records
   - Modify existing student info
   - Search by admission number or phone
   - List students with pending fees
4. Generate report cards as PDFs and (optionally) email them.

---

## 🗂️ Project Structure

```
SchoolDesk/
├── main.py       # Main application script
├── logo.jpeg     # School logo for report card
```

---

## 🖼️ Database Structure

**Table: `student`**

| Column        | Type         | Description |
|---------------|--------------|-------------|
| ADMISSION_NO  | BIGINT (PK)  | Admission number |
| NAME          | VARCHAR(20)  | Student name |
| CLASS_        | VARCHAR(10)  | Class |
| FATHER        | VARCHAR(20)  | Father's name |
| MOTHER        | VARCHAR(20)  | Mother's name |
| ADM_DATE      | VARCHAR(15)  | Admission date |
| FEES          | BIGINT       | Total fees |
| BALANCE       | BIGINT       | Pending fees |
| PHONE         | VARCHAR(13)  | Contact number |
| EMAIL         | VARCHAR(30)  | Email ID |
| ADDRESS       | VARCHAR(100) | Address |
| DOB           | VARCHAR(15)  | Date of birth |

---

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/SchoolDesk.git
   cd SchoolDesk
   ```

2. **Install dependencies**:
   ```bash
   pip install mysql-connector-python fpdf pillow
   ```

3. **Set up MySQL**:
   - Create a MySQL user and password, then update them in `main.py`
   - The program will auto-create the `school` database and `student` table if they don’t exist

4. **Add Logo**:
   - Place `logo.jpeg` in the same folder as `main.py`

5. **Run the application**:
   ```bash
   python main.py
   ```

---

## 📊 Output

- **Pending Fees Report** – Lists students with unpaid fees  
- **Search Results** – Student details fetched by admission number or phone  
- **PDF Report Card** – Generated in real-time with student details, marks, and logo  

---

## ✅ To-Do / Future Improvements

- Add GUI interface for non-technical users
- Support multiple classes/sections
- Add attendance management
- Export data to Excel format
- Improve email formatting and attachments

---

## 📄 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute, with proper attribution.

---

## 👨‍💻 Author

**Divyam Sethi**  
🔗 [GitHub](https://github.com/sethidivyam)  
📧 [Email](mailto:divyamsethi1804@gmail.com)

---

## ⭐️ Support

If you found this project helpful, please ⭐ the repository and share it with others!
