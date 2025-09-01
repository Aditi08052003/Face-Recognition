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
