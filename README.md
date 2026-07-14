# Face Recognition Attendance System

## 📌 Project Overview

The Face Recognition Attendance System is a desktop application developed using Python, OpenCV, Tkinter, and SQLite. It automates attendance management by recognizing registered users through a webcam and recording attendance with the current date and time.

This project eliminates manual attendance processes, reduces proxy attendance, and improves accuracy and efficiency.

---

## 🚀 Features

- Capture student face images
- Train face recognition model using OpenCV LBPH
- Real-time face recognition through webcam
- Automatic attendance marking
- Attendance stored in CSV file
- Attendance stored in SQLite database
- Simple GUI using Tkinter
- User-friendly interface

---

## 🛠 Technologies Used

- Python
- OpenCV
- Tkinter
- SQLite
- Pandas
- NumPy

---

## 📂 Project Structure

```
Face-Recognition-Attendance-System/
│
├── dataset/
├── attendance.py
├── capture_images.py
├── train_model.py
├── database.py
├── main.py
├── trainer.yml
├── labels.txt
├── attendance.csv
├── database.db
├── haarcascade_frontalface_default.xml
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/Face-Recognition-Attendance-System.git
```

### 2. Move to the project folder

```bash
cd Face-Recognition-Attendance-System
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python main.py
```

---

## 📋 Workflow

1. Capture student images.
2. Train the face recognition model.
3. Start attendance.
4. Face is recognized.
5. Attendance is automatically recorded in CSV and SQLite database.

---

## 🎯 Future Enhancements

- Student registration form
- Admin login
- Attendance reports
- Export attendance to Excel
- Cloud database integration
- Email attendance reports

---

## 👨‍💻 Author

**Sunneshwar Reddy**

Computer Science and Engineering Student

---
