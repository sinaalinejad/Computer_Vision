## Mask Overlay (Q3.ipynb)
The task is to put the mask on Einstein's face.
Two steps:
- Finding face landmarks or key points using dlib library.
- Use special face key points and perspective transformation to put the mask on the face.


## CamScanner program (Q4.ipynb)
we have different types of transformations on images like rigid, affine, and perspective. The most general one is perspective transformation which  
contains scaling, translation, rotation, and tilting. 4 points is enough for this transformation to achieve the original version of an image.
Two main steps:
- Finding 4 corners of the paper: I did this using a combination of OpenCV functions like findContours, arcLength, approxPolyDP
- Using those 4 points to get the perspective transform: For this part I used cv2.getPerspective and cv2.warpPerspective functions from OpenCV


## Corner Detection using Harris algorithm (Q5.ipynb)
There are two versions for this, one with just numpy library and the other with OpenCV library.
