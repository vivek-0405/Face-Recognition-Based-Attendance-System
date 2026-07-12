# Face Recognition Based Attendance System

## Overview

The Face Recognition Based Attendance System is an AI-powered application that automates attendance marking using computer vision and machine learning. The system detects and recognizes faces in real time through a webcam and records attendance with the person's name, date, and time.

This project eliminates the need for manual attendance, making the process faster, more accurate, and more secure.

---

## Features

* Real-time face detection using OpenCV.
* Face recognition using the K-Nearest Neighbors (KNN) algorithm.
* Automatic attendance marking.
* Stores attendance with date and timestamp.
* User-friendly interface built with Streamlit.
* Displays attendance records in a table.
* Automatic attendance file generation for each day.

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Pandas
* Scikit-learn
* Streamlit
* Pickle

---

## Project Structure

```text
Face-Recognition-Based-Attendance-System/
│
├── app.py
├── add_faces.ipynb
├── test.ipynb
├── Attendance/
|   ├──Attendance_23-06-2026.csv
├── Data/
│   ├── faces_data.pkl
│   ├── names.pkl
│   └── haarcascade_frontalface_default.xml
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How It Works

1. Register a user's face using the face registration script.
2. The captured face images are processed and stored.
3. Train the face recognition model.
4. Launch the Streamlit application.
5. The webcam detects and recognizes faces in real time.
6. Attendance is automatically recorded with the person's name, date, and time.

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Face-Recognition-Based-Attendance-System.git
```

### 2. Navigate to the Project Folder

```bash
cd Face-Recognition-Based-Attendance-System
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

---

## Attendance Output

The system automatically creates a CSV file containing:

* Name
* Time
* Date

Attendance records are saved inside the **Attendance** folder.

---

## Future Improvements

* Face recognition using deep learning models.
* Database integration (MySQL/MongoDB).
* Cloud-based attendance storage.
* Admin login dashboard.
* Email notification after attendance.
* Anti-spoofing (photo detection).
* Attendance analytics and reports.

---

## Author

**Vivek**

B.Tech (Artificial Intelligence & Machine Learning)

---

## License

This project is developed for educational and learning purposes.
