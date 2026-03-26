Project Title

Face Detection and Attendance System using OpenCV and Face Recognition

**Objective**

The objective of this project is to develop a real-time face recognition system that automatically marks attendance using a webcam.

**Description**

This project uses computer vision and machine learning techniques to detect and recognize human faces. The system captures live video through a webcam, detects faces in each frame, compares them with pre-stored images, and marks attendance for recognized individuals.
The attendance is stored in a CSV file with the name of the person and the timestamp.

**Technologies Used**
Python
OpenCV (cv2)
face_recognition (dlib-based)
NumPy
CSV file handling
**Project Structure**
Project Folder/
│
├── FaceReg.py
├── Attendance.csv
└── Project Image/
   
**How It Works**
Images of known individuals are stored in a folder.
Each image is converted into a facial encoding.
The webcam captures live video frames.
Faces in the frame are detected and encoded.
The system compares live encodings with stored encodings.
If a match is found, the name is displayed and attendance is marked.
If no match is found, the face is labeled as "UNKNOWN".

**Installation**

Install required libraries:

pip install opencv-python face_recognition numpy
How to Run
Place your images in the dataset folder
Run the script:
python FaceReg.py
Press Q to exit the webcam
**Output**
Real-time face detection through webcam
Recognized names displayed on screen
Attendance stored in Attendance.csv
Advantages
Reduces manual attendance errors
Prevents proxy attendance
Fast and automated system
Limitations
Accuracy depends on image quality
Requires proper lighting
Limited performance with large datasets
Future Enhancements
Add GUI interface
Integrate with database (MySQL/Firebase)
Improve accuracy using deep learning models
Add mask detection support
Conclusion

The system successfully demonstrates the use of face recognition for automating attendance. It is efficient, reliable, and can be extended for real-world applications.
