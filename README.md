# Real-Time-Face-Recognition-System
A Real-time face recognition attendance system using Python and OpenCV. Detects and identifies faces via webcam and marks attendance automatically with date and time. Eliminates manual entry, reduces proxy attendance, and ensures fast, accurate, and contactless tracking.
# 🎯 Real-Time-Face-Recognition-System

An intelligent attendance system that uses real-time face recognition to automatically mark attendance. This project eliminates manual attendance processes and provides a fast, secure, and contactless solution.

---

## 🚀 Features

* 🎥 Real-time face detection & recognition
* 🧾 Automatic attendance marking
* 📅 Date & time-based attendance logging
* 📊 Stores attendance records (CSV/Database)
* ⚡ Fast and efficient processing
* 👥 Supports multiple users

---

## 🛠️ Tech Stack

* Python 🐍
* OpenCV 👁️
* NumPy
* Face Recognition Library / Haar Cascade
* CSV / Pandas (for attendance storage)

---

## 📂 Project Structure

├── dataset/              # Face images dataset
├── trainer/              # Trained model files
├── attendance.csv        # Attendance records
├── dataset_creator.py    # Capture face data
├── trainer.py            # Train model
├── recognizer.py         # Recognize faces & mark attendance
└── README.md

---

## ⚙️ How It Works

1. 📸 Capture images of users and store in dataset
2. 🧠 Train the face recognition model
3. 🎥 Run the system using webcam
4. ✅ Recognized faces are marked present with timestamp
5. 📊 Attendance is saved automatically

---

## ▶️ Installation

git clone https://github.com/your-username/face-attendance-system.git
cd face-attendance-system
pip install -r requirements.txt

---

## ▶️ Usage

### Step 1: Capture Dataset

python dataset_creator.py

### Step 2: Train Model

python trainer.py

### Step 3: Start Attendance System

python recognizer.py

---

## 📸 Output

* Detects and recognizes faces in real-time
* Marks attendance automatically
* Saves records with name, date, and time

---

## 🎯 Applications

* 🏫 School / College Attendance
* 🏢 Office Employee Tracking
* 🔒 Secure Access Systems

---

## 🚀 Future Improvements

* Add database integration (MySQL / Firebase)
* Build web dashboard for attendance tracking
* Add mask detection / spoof detection
* Deploy as a web or mobile application

---

## 🤝 Contributing

Feel free to fork this project and improve it!

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
