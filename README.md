# 🖼️ Dataset Image-Label Renamer

This script safely renames paired image-label files for dataset splits (`train`, `test`, `valid`) while maintaining correct matching between images and their corresponding label files.

---

## ✅ Features
- Works on `train`, `test`, and `valid` splits.
- Avoids filename conflicts using a two-step temporary renaming.
- Checks for missing labels before renaming.
- Generates uniform file names: `sample_00001.jpg`, `sample_00001.txt`, etc.

---

## 🧩 Folder Structure Example:
rename-dataset/
│
├── rename_dataset.py
├── README.md
└── requirements.txt
