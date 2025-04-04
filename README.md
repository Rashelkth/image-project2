## Image Generation & Autoencoder Project

## 📌 Project Overview
This project applies transformations (flip, rotate, noise) to images and trains an autoencoder to reconstruct them.

## 🚀 How to Run

### 1️⃣ Install Dependencies  
Ensure you have Python installed, then run:  
```bash
pip install -r requirements.txt

### 2. Run the Image processing & Authencoder Training
python main.py

### 3. Dependencies:
Python 3.x
TensorFlow
OpenCV
NumPy
Matplotlib

### 4. How to Upload Big Files in Git (Safely & Effectively)
 Step 1: Understand the Git File Size Limit
  GitHub’s hard file size limit is 100 MB per file.
  Git will warn you if a file is over ~50 MB.
  For larger files, you should use Git LFS (Large File Storage).
Step 2: Install Git LFS (Large File Storage)
  git lfs install
Step 3: Track Your Large Files
  git lfs track "*.zip"
  git lfs track "*.png"
  git lfs track "*.h5"   # (for machine learning models, for example)
  git add .gitattributes
Step 4: Add, Commit, and Push Your Files
  git add large_file.zip
  git commit -m "Added large file with Git LFS"
  git push origin main

### Author
Developed by: [Rashel Hasan]
