"# pupil-detection--19-27-100-" 

PUPIL detection from eyes images using OpenCV 3 and Python 3.6.


Detecting PUPIL or EyeBall using OpenCV.
Algorithm

    1.First take the eye image.
    2.Make it invert.
    3.Convert it to gray scale.
    4.Apply Erosion Transform.
    5.Use binary filter taking threshold value 210.
    6.Find the biggest object.
    7.Find that object's center point and height.
    8.Highlight that circle.



Color Image Denoising and Gaussian Blur techniques are used for pre-processing the eye image before applying inversion filter over it. 
For segmentation, the contour with center nearest to center of image is filtered. Eyeball will be near to center of eye image Rest 
algorithm for pupil detection is same as in detect_pupil.py


Requirements:
	1. OpenCV
	2. Numpy

Run:
	1. Navigate inside folder
	2. Install the requirements
	3. In cmd run Command 'python pupilDetection.py'



**Project by:
Prajwal Bhagat 2017BTECS00019
Utkarsh Kendre 2017BTECS00027
Mangesh Puri 2017BTECS00100**
