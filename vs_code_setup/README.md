# 🖥️ VS Code Setup for Python & OpenCV

This guide will help you set up **Visual Studio Code (VS Code)** for Python development and install **OpenCV** for computer vision projects.

---

## ✅ What You’ll Learn
- Install the Python
- Install VS Code and Python extension
- Create and activate a virtual environment
- Install OpenCV
- Run a test webcam script in VS Code

---

## 📦 Prerequisites
- Python 3.8 or higher installed ([Download Python](https://www.python.org/downloads/))
- VS Code installed ([Download VS Code](https://code.visualstudio.com/))

---

## 🔍 Step 1: Install VS Code
1. Download VS Code from [https://code.visualstudio.com](https://code.visualstudio.com)
2. Install and open VS Code

---

## 🔍 Step 2: Install Python Extension
1. Open VS Code
2. Go to **Extensions** (left sidebar)
3. Search for **Python** and install the official extension

---

## 🔍 Step 3: Create Project Folder
- Create a folder, e.g., `opencv_setup`
- Open it in VS Code (**File → Open Folder**)

---

## 🔍 Step 4: Setup Virtual Environment
Open VS Code terminal and run:
```bash
# Create virtual environment
python -m venv .venv

# Activate (Windows)
.venv\Scriptsctivate

# Activate (macOS/Linux)
source .venv/bin/activate
```

You should see `(.venv)` in your terminal prompt.

---

## 🔍 Step 5: Install OpenCV
```bash
pip install opencv-python
```
Verify installation:
```python
import cv2
print(cv2.__version__)
```

---

## 🔍 Step 6: Run Test Script
Create `test.py`:
```python
```

Run in terminal:
```bash
python test.py
```

---

## ✅ TODO List for Learners
- [ ] Install the Python
- [ ] Install VS Code
- [ ] Install Python extension
- [ ] Create project folder and open in VS Code
- [ ] Setup virtual environment
- [ ] Install OpenCV
- [ ] Run webcam test script

---

