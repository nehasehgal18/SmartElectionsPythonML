
# 🗳️ Smart Elections – Voter Identification Using Machine Learning

A Python-based machine learning project that uses **OpenCV** for facial recognition and **scikit-learn** for classification, designed to enhance the voting process through intelligent automation and verification.  

> ⚠️ This project uses your computer’s webcam for real-time facial detection and requires local execution.  

---

## 🚀 Features

- 🎥 Real-time face capture using OpenCV
- 🤖 Machine Learning model for user verification/classification
- 📊 Data preprocessing and model training with `scikit-learn`
- 🧪 Simple command-line interaction for simulation of a voting process
- ✅ Designed to enhance electoral security and automation

---

## 🛠️ Tech Stack

- **Python 3.9+**
- `opencv-python`
- `scikit-learn`
- `numpy`, `pandas`
- `pywin32` *(Windows only, for webcam access via OpenCV – replace/remove for deployment)*

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/smartelectionspythonml.git
cd SMARTELECTIONFG
pip install -r requirements.txt
```

> ✅ Make sure your system has a camera (webcam) and Python 3.9+ installed.
> I have used Python 3.13.2 version

---

## 🧑‍💻 How to Run

```bash
python give_vote.py
```

This script will access your webcam, capture facial data, and simulate a voting interface based on the machine learning model.

---

## 📁 Project Structure

```
📦 SMARTELECTIONFG/  
┣ 📜 add_faces.py            # Script to register/add new faces  
┣ 📜 give_vote.py            # Main voting interface script  
┣ 🖼 background.png          # Background image used in UI  
┣ 📜 requirements.txt        # List of Python dependencies  
┣ 📜 README.md               # Project documentation  
┣ 📊 Votes.csv               # Stores vote records  
┗ 📁 data/                   # Directory to store user face data
```
