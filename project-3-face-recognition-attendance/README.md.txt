# 👤 Face Recognition Attendance System

## 📌 Overview

This project implements a face recognition-based attendance system using DeepFace.

The system extracts facial embeddings from images, compares them with a database, and automatically records attendance with timestamps.



## 🚀 Features

* Face recognition using DeepFace (FaceNet)
* Custom dataset (multiple images per person)
* Embedding-based identity matching
* Distance-based similarity calculation
* Automatic attendance logging (CSV)
* Duplicate prevention



## 🧠 How It Works

1. Load dataset and extract embeddings
2. Average embeddings for each person
3. Convert new image into embedding
4. Compare with database using Euclidean distance
5. Identify person
6. Record attendance with timestamp


## 🛠️ Technologies Used

* Python
* DeepFace
* NumPy
* Pandas
* OpenCV



## 📂 Project Structure

project-3-face-recognition-attendance/
├── main.ipynb
├── README.md
└── results/
└── attendance.csv



## 🎯 Output

* Recognized identity
* Distance score
* Attendance CSV file with timestamps


## 📌 Author

GHITA OUARZI
