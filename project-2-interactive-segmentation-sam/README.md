# 🧩 Interactive Image Segmentation using SAM

## 📌 Overview

This project implements an interactive image segmentation system using the Segment Anything Model (SAM).
Users guide segmentation with foreground and background points (via sliders/buttons in Colab).



## 🚀 Features

* Interactive segmentation (coordinate-based input)
* Foreground / background point control
* Multi-point refinement
* Mask overlay visualization
* Object extraction (background removal)
* Save results (`mask.png`, `segmented.png`)


## 🛠️ Tech Stack

* Python, OpenCV, NumPy, Matplotlib
* Segment Anything Model (SAM)



## ▶️ How to Run (Colab)

1. Install dependencies
2. Download SAM checkpoint
3. Upload an image (e.g., `outfit.png`)
4. Move sliders (X, Y) → click *Add Point*
5. Switch mode (Foreground / Background) to refine
6. Click **Save Result**

📸 Results
<img width="736" height="1308" alt="77aec4f553aee5eefb7f531ecc2feb6d" src="https://github.com/user-attachments/assets/71fdfb7d-443e-4ecd-9a92-e5542881b62e" />


## 📂 Structure

project-2-interactive-segmentation-sam/
├── x.ipynb
├── README.md
└── results/
├── mask.png
└── segmented.png



## ⋆｡‧˚ʚ🍓ɞ˚‧｡⋆ Author⋆｡‧˚ʚ🍓ɞ˚‧｡⋆

ghita ouarzi
