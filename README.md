# Face Attendance System

An attendance management system using OpenCV and facial recognition, with a graphical interface built with CustomTkinter.

## Features

- Real-time face detection and recognition
- Automatic attendance marking for "start" and "end" of sessions
- Anti-spoofing (basic eye detection)
- Manual marking of absentees
- Dataset analysis and verification
- Improved LBPH model training
- Multi-student face collection
- Export attendance to CSV

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/face-attendance-system.git
2.Navigate to the project folder:
cd face-attendance-system
3.Install dependencies:
pip install -r requirements.txt
Usage
Run the main script:
python your_script.py

Use the graphical interface to:
Collect faces for new students
Train the model
Start/end sessions to mark attendance
View attendance CSV
Analyze dataset and test recognition

Folder Structure
dataset/           # Stores images of students
model/             # Contains trained models and labels
attendance.csv     # CSV file with attendance records
collecte_faces.py     # Main program

Notes
Minimum 30 images per student recommended for accurate recognition.
Confidence threshold for recognition: 70
Absentees are automatically marked after "End of session".
