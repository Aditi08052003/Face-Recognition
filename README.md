# Face Recognition — Attendance Tracking Demo

A Python-based face recognition tool that detects and identifies faces from a live webcam feed (or uploaded images). It’s designed as a building block for automated attendance systems and showcases real-time detection, enrollment, and recognition workflows.

---

##  Features

- **Enroll** new faces using your webcam or images.
- **Recognize** enrolled individuals in real time.
- **Attendance logging** (timestamp + name) into CSV.
- Modular design separating CLI and processing logic.

---

##  Tech Stack

- **Language:** Python 3.x
- **Computer Vision & ML:** OpenCV, NumPy, face detection (e.g., Haar Cascades or DNN)
- **CLI / Structure:** Modular scripts (`face.py`), clean folder layout
- **Data Storage:** Organized `Face_Images/` per person, simple CSV for logs

---

##  Project Structure

Face-Recognition/
├── face_recognition/          # Source code package
│   ├── __init__.py
│   ├── face.py                # Main CLI logic (enroll/recognize)
│   ├── detect.py              # Face detection functions
│   ├── utils.py               # Helper functions (CSV logging, etc.)
│
├── data/                      # Sample or small demo data
│   ├── Face_Images/           # Person images (tiny sample, not full dataset)
│   └── Attendance/            # Logs (CSV files)
│
├── tests/                     # Unit tests
│   └── test_detect.py
│
├── requirements.txt           # Dependencies (opencv-python, numpy, etc.)
├── .gitignore                 # Ignore venv, __pycache__, large files
├── README.md                  # Project documentation
├── LICENSE                    # (MIT recommended)
└── app.py                     # Optional: Streamlit/Flask app for UI

