
# Face Recognition Based Attendance System

# Overview
The Face Recognition Based Attendance System is a desktop application that leverages facial recognition technology to automate attendance tracking. This system allows users to capture their facial images using a webcam, train the system with their information, and then use the face detection feature to mark their attendance.

# Features
Capture facial images using a webcam\
Store necessary information using the student panel page\
Train the model with the captured images\
Perform face detection to mark attendance\
Automatic attendance logging in a CSV file\

# Prerequisites
To run the Face Recognition Based Attendance System, you need to have the following installed on your system:

Python 3 (version 3.6 or later)\
mysql-connector-python\
tensorflow\
OpenCV\
tkinter\
Pillow\
NumPy 







## Installation

1. Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/Taha533/Face-Recognition-based-Attendance-System.git
```
2. Navigate to the project directory:

```bash
cd Face-Recognition-based-Attendance-System
```
3. Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

## Screenshots

1. Login Page

![image](https://github.com/Taha533/Face-Recognition-based-Attendance-System/blob/main/Images_GUI/Login%20Page.PNG)

2. Student Panel

![image](https://github.com/Taha533/Face-Recognition-based-Attendance-System/blob/main/Images_GUI/main_page.PNG)

3. Train Panel

![image](https://github.com/Taha533/Face-Recognition-based-Attendance-System/blob/main/Images_GUI/train_pannel.PNG)

4. Face Detector panel

![image](https://github.com/Taha533/Face-Recognition-based-Attendance-System/blob/main/Images_GUI/face_detector.PNG)

5. Attendance panel

![image](https://github.com/Taha533/Face-Recognition-based-Attendance-System/blob/main/Images_GUI/attendance_pannel.PNG)

    
## Usage

1. Fill in the necessary information using the student panel page. Provide details such as name, ID, and any other relevant information.

2. Train the system with your facial images by navigating to the Data Train page. Follow the instructions provided on the page to capture multiple facial images using your webcam. The system will use these images to learn and recognize your face.

3. Once the training process is complete, the model will be ready with your information.

4. To mark your attendance, open the Face Detector page and click the face detector button. This will open your webcam and start detecting faces. If your face matches one of the trained images, your attendance will be logged in a CSV file.

# Contributing
Contributions to the Face Recognition Based Attendance System are welcome. If you have any ideas, suggestions, or improvements, please submit a pull request. Make sure to follow the established coding style and include detailed information about your changes.

# Acknowledgements
- The Face Recognition Based Attendance System is built specially on top of the OpenCV, tkinter, and NumPy libraries.
- Special thanks to the open-source community for their valuable contributions

# Contact
If you have any questions, feedback, or suggestions, please feel free to reach out to me:\
Bahauddin Taha\
Email: taha15@cse.pstu.ac.bd\
GitHub: https://github.com/Taha533 \
Linkedin: https://www.linkedin.com/in/bahauddin-taha-67617315b/



