# Invisibility
This app uses color segmentation and a bit of image processing to replace the foreground object of interest with the background.
You can take a bedsheet and apply color segmentation on it. After that take a picture of the background and place the bedsheet over yourself to virtually disappear, or make some part of your body disappear.

# Dependencies:
	1	Python 3
	2	Numpy
	3	OpenCV (Python)

## Installation for OpenCV:
Open Command Prompt (Windows) or Terminal (Linux) and type in the following command:<br />pip install opencv-python<br />

# How to use?
	1	Run the invisible cloak.ipynb (jupyter nbconvert --execute invisible-cloak.ipynb)
	 (While Running it, make sure nobody is infront of the webcam)
	2	An window showing the video will pop up.
	3	take a red piece of cloth in front of it and the magic will happen.


	I use the range 0-10 and 170-180 to avoid detection of skin as 	red. High range of 120-255
	for saturation is used because our cloth should be of highly saturated red color.
	The lower range of value is 70 so that we can detect red color in the wrinkles of the cloth as well.


![](https://github.com/YKalashnikov/Invisibility/blob/master/image.gif)