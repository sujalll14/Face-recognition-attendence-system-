# Face-recognition-attendence-system- 

An AI-powered attendance management system that automatically detects and marks student attendance using facial recognition — eliminating manual roll calls with a smart biometric approach.

This project combines a Python-based facial recognition backend (Google Colab notebook) with a futuristic web-based UI to automate student attendance tracking. Teachers enroll students by uploading individual portraits, then upload group class photos per subject. The system identifies each face and marks attendance as Present or Absent per subject, exporting the results as an Excel report.

Features
📸 Student Enrollment — Register up to 8 students via individual portrait uploads
🔍 Automatic Face Detection — Detects and identifies multiple faces in a single group photo
📚 Subject-wise Attendance — Tracks attendance separately for Maths, Science, and English
📊 Live Accuracy Meter — Animated ring chart showing recognition rate per subject
🖥️ Interactive Web Dashboard — Cyberpunk-styled UI with drag-and-drop uploads, student grid, and attendance table
📥 Excel/CSV Export — One-click download of the full attendance report
☁️ Google Colab Ready — Backend runs entirely in-browser via Colab, no local setup needed
🔄 Simulate Scan — Built-in simulation mode in the UI for demo/testing without real images

Backend (Colab Notebook)
Open Google Colab and upload `face_recognition_attendance_system.ipynb`
Run the first cell to install dependencies:
```bash
   pip install face_recognition opencv-python
   ```
Run all cells in order and follow the upload prompts
Frontend (Web UI)
Open `attendance_ui133.html` directly in any modern browser — no server needed
Use the 3-step workflow: Enroll → Scan → Export

Project Structure
```
├── face_recognition_attendance_system.ipynb  # Colab backend
├── attendance_ui133.html                      # Web UI dashboard
├── known_faces/                               # Auto-created; registered student images
├── attendance_report.xlsx                     # Auto-generated output (notebook)
└── face_recognition_attendance_system.md      # This README
Web UI
Live attendance register with Present/Absent badges
Per-subject attendance bars + animated accuracy ring
System log with timestamped events

