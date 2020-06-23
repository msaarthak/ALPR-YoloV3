# ALPR-yolov3
We can use Object Detection algorithm to detect the license plate from an image or video and then we can perform OCR or Optical Character Recognition on the cropped license plates. By splitting the problem into two components, we have made it easier and efficient to perform License Plate Recognition (LPR). Hence, the problem can be divided into two sub-problems as we mentioned above: 

1. Number Plate Detection. This problem can be tackled using Object Detection approach where we need to train our model using the car/other vehicle images with number plates. 

2. Extracting text from the detected Number Plate. This problem can be solved using OCR (Optical Character Recognition) which can be helpful in extracting alphanumeric characters from cropped Number Plate images.

This problem was solved with help of code from:- https://github.com/mehulgupta2016154/TCS_HUMAIN

Mehul Gupta is a Data Science Intern based in India and has an impressive range of articles on medium:- https://medium.com/@mehulgupta_7991
He has guided me along the way to understand his project.

The code was written in python and executed on Google colab. The first part of the problem was executed on Google Colab using the powerful GPUs given by google. The second part of the problem which was Character recognition using open source APis by Google OCR and Microsoft Azure OCR. 

My supervisor Dr.Shan Du also gave me guidance and gave feedback throughout the developement of this project. Her work can be found here:-
http://www.ece.ubc.ca/~shand/
