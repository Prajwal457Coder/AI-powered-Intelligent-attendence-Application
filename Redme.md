# 🎓 SnapClass – AI Powered Attendance System

SnapClass is an AI-powered attendance management system that automates classroom attendance using **Face Recognition**, **Voice Recognition**, and **QR Code-based Enrollment**. It helps teachers take attendance quickly while reducing manual effort and proxy attendance.

---

# 🚀 Features

* 👤 AI Face Recognition Attendance
* 🎤 AI Voice Recognition Attendance
* 📷 QR Code Based Subject Enrollment
* 👨‍🏫 Teacher Dashboard
* 👨‍🎓 Student Dashboard
* 📊 Attendance Analytics
* 📝 Attendance History
* 🔒 Secure Teacher Authentication
* ☁️ Supabase Cloud Database
* ⚡ Modern Streamlit UI

---

# 🛠 Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### Database

* Supabase

### Machine Learning

* scikit-learn
* dlib
* face_recognition
* Resemblyzer
* Librosa

### Image Processing

* Pillow

### Security

* bcrypt

### QR Code

* Segno

---

# 📁 Project Structure

```
SnapClass/
│
├── app.py
├── requirements.txt
├── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   ├── screens/
│   ├── ui/
│   └── utils/
│
├── models/
├── assets/
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/your-username/SnapClass.git

cd SnapClass
```

---

## 2. Create Virtual Environment

```bash
python -m venv venv
```

A virtual environment isolates project dependencies so that different Python projects do not conflict with each other.

---

## 3. Activate Virtual Environment

### Windows

```bash
.\venv\Scripts\Activate.ps1
```

Run this command every time you reopen VS Code.

---

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5. Run the Application

```bash
streamlit run app.py
```

---

# 📦 Important Libraries

## Streamlit

Used to build the complete web interface.

```
pip install streamlit
```

---

## Supabase

Cloud database for storing:

* Students
* Teachers
* Subjects
* Attendance
* Face Embeddings
* Voice Embeddings

```
pip install supabase
```

---

## scikit-learn

Machine Learning algorithms used for face recognition classification.

```
pip install scikit-learn
```

---

## dlib-bin

Provides facial landmark detection and face encoding support.

```
pip install dlib-bin
```

---

## face_recognition_models

Downloads pretrained facial landmark models.

```
git+https://github.com/ageitgey/face_recognition_models
```

---

## setuptools

Required for installing face recognition dependencies.

```
setuptools<70.0.0
```

---

## bcrypt

Hashes teacher passwords securely before storing them in the database.

```
pip install bcrypt
```

---

## Pillow

Used for image preprocessing before AI prediction.

```
pip install pillow
```

---

## Segno

Generates QR Codes for instant classroom enrollment.

```
pip install segno
```

---

## Librosa

Processes classroom audio recordings.

Functions include:

* Audio Loading
* Noise Reduction
* Audio Segmentation
* Feature Extraction

```
pip install librosa
```

---

## Resemblyzer

Creates Voice Embeddings that allow AI to compare two voices.

```
pip install resemblyzer
```

---

# 🤖 AI Pipeline

## Face Attendance

1. Capture student face
2. Detect face using dlib
3. Generate face embedding
4. Compare with stored embeddings
5. Mark attendance

---

## Voice Attendance

1. Record classroom audio
2. Extract speaker embeddings
3. Compare with stored voice embeddings
4. Identify students
5. Mark attendance

---

## QR Enrollment

1. Teacher creates a subject
2. System generates QR Code
3. Student scans QR Code
4. Student joins subject automatically

---

# 🔒 Security

* Password Hashing using bcrypt
* Face Embeddings
* Voice Embeddings
* Secure Database using Supabase

---

# 📸 Screens

* Home Page
* Teacher Dashboard
* Student Dashboard
* Face Attendance
* Voice Attendance
* QR Enrollment
* Attendance Reports

(Add screenshots here)

---

# 📌 Future Improvements

* Mobile Application
* Multi-face Live Attendance
* Anti-Spoofing Detection
* Liveness Detection
* Voice Anti-Replay Detection
* Email Attendance Reports
* Attendance Analytics Dashboard
* SMS Notifications
* Cloud Deployment

---

# 👨‍💻 Developed By

**Prajwal Kumbhare**

B.Tech CSE (Data Science)

AI • Machine Learning •