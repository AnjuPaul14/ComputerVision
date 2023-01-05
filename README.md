# ComputerVision
My computer vision projects

The folder includes 4 files:

1) haarcascade_frontalface_default.xml - The filters required to identify the face
2) haarcascade_eye.xml - The filters required to identify the eyes
3) haarcascade_smile.xml - The filters required to identify the smile
4) Smile_Detector.py - The python Code

The implementation of the code is through the usage of OpenCV libraries. The stages through the code are
1) Import the libraries
2) Read the haarcascasde filters
3) Define a detector function to identify the face and then eyes inside the identified area , and then smile inside the face.
   It also draws rectangles across the features(face, eyes, and smile with different colours)
4) Use the webcam of the laptop to capture the video and take the last frame from it
5) Change the colour frame to gray scale in order to apply the filters
6) Apply the detector funtion to draw the rectangles
7) Do this process continuosly and then break when needs to stop
8) Clear all the files.

