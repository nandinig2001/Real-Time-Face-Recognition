# Real-Time-Face-Recognition
Real Time Face Recognition project for detecting the faces and displaying the names of the faces based on the data already fed.
A real time face recognition system is capable of identifying or verifying a person from a video frame. To recognize the face in a frame,
first we need to detect whether the face is present in the frame.


In OpenCV, we have several trained  Haar Cascade models which are saved as XML files. Instead of creating and training the model from scratch,
we use this file. I have used “haarcascade_frontalface_default.xml” file in this project.

Steps:
1 Create a folder containing the clear images of faces you want to detect and provide the path for those images to the code.
2 Download the required modules.

Modules:
pip3 install numpy
pip3 install dlib
pip3 instal opencv-python
pip3 install face_recognition

NOTE:
In Windows, download Visual Studio with C++ compiler before installing face_recognition module on VSCode.

Domain:
Python
OpenCV
