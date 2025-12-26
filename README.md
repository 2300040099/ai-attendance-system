# AI Attendance System using Facial Recognition

This project implements an automated attendance system using facial recognition.
It captures face data, trains a recognition model, and marks attendance in real time.

## Technologies Used
- Python
- OpenCV
- LBPH Face Recognizer
- Computer Vision

## Project Files
- attendance.py  
  Trains the face recognition model and marks attendance using webcam input.

- data_creation.py  
  Captures face images and creates a dataset for training.

- haarcascade_frontalface_default.xml  
  Haar Cascade classifier used for face detection.

## Working Flow
1. Run data_creation.py to collect face images.
2. Train the model using the collected dataset.
3. Run attendance.py to recognize faces and mark attendance in a CSV file.

## Output
- Recognized faces displayed on live camera feed
- Attendance stored in `attendance.csv`

## Applications
- Educational institutions
- Smart classrooms
- Contactless attendance systems

## Future Enhancements
- Improve accuracy using deep learning
- Database integration
- GUI-based interface
