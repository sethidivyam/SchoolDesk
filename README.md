# SchoolDesk

SchoolDesk is a Python-based School Management System designed to simplify student record handling, exam result processing, and report card generation. It uses **MySQL** for database management and supports automated PDF generation for reports.

---

## 📌 Features
- 🗂 **Student Record Management** – Add, update, delete, and search student details.
- 📊 **Exam & Result Processing** – Manage periodic and final exam scores.
- 📝 **PDF Report Card Generation** – Auto-generate professional report cards.
- 🔗 **MySQL Integration** – Store and retrieve all data securely.
- ⚡ **User-Friendly Interface** – Simple, intuitive design for smooth workflow.

---

## 🚀 Installation

1️⃣ **Clone the Repository**  
git clone https://github.com/sethidivyam/SchoolDesk.git  
cd SchoolDesk  

2️⃣ **Install Requirements**  
pip install -r requirements.txt  

3️⃣ **Configure Database**  
Edit `config.py` with your MySQL credentials:  
DB_HOST = "localhost"  
DB_USER = "root"  
DB_PASSWORD = "your_password"  
DB_NAME = "school_db"  

4️⃣ **Run the Application**  
python main.py  

---

## 📂 Project Structure
SchoolDesk/  
│-- main.py              # Entry point  
│-- config.py            # Database configuration  
│-- requirements.txt     # Python dependencies  
│-- /modules             # App modules  
│-- /templates           # PDF templates  
│-- /__pycache__         # Cached files  
│-- README.md            # Project documentation  

---

## 🛠 Technologies Used
- Python 3  
- MySQL  
- ReportLab (PDF generation)  
- Tkinter (UI, optional)  

---

## 📜 License
This project is licensed under the MIT License – feel free to use and modify.

---

## 💡 Author
Divyam Sethi  
GitHub: https://github.com/sethidivyam
