# 👁️ Real-Time People Detection, Tracking & Counting

## 📌 Project Overview

This project implements a complete computer vision pipeline to detect, track, and count people in a video.

It uses a deep learning model for object detection and a tracking algorithm to assign unique IDs to each person across frames.



## 🚀 Features

* Detect people in video using YOLOv8
* Track each person with a unique ID (DeepSORT)
* Count total number of unique people
* Real-time visualization with bounding boxes and IDs



## 🧠 How It Works

1. Video is processed frame by frame
2. YOLOv8 detects people in each frame
3. DeepSORT assigns a unique ID to each detected person
4. IDs are stored to count unique individuals
5. Results are displayed with bounding boxes and counts


## 🛠️ Technologies Used

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* DeepSORT

---

## 📂 Project Structure

```
project-1-people-tracking/
│
├── main.ipynb       # Main notebook (Colab)
├── README.md        # Project documentation
└── results/
    └── output.png   # Sample result




## 🎯 Output

* Bounding boxes around detected people
* Unique ID assigned to each person
* Total count of people displayed



## 🔮 Future Improvements

* Line crossing detection (IN / OUT counting)
* Trajectory tracking
* Heatmap visualization
* Custom dataset training



## 📌 Author

GHITA OUARZI
