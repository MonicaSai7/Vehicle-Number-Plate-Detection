# Vehicle-Number-Plate-Detection

The dataset considered is of Indian Number Plates in the form of a JSON file. The file consists of links for each vehicle image including the coordinates of the number plate in the image.
The main purpose of this project is to extarct the number plates from the images and recognise the text on the number plates.

## Dependencies:
#### Python3<br/>pytesseract<br/>Tesseract 4<br/>OpenCV<br/>PILLOW<br/>urllib<br/>
## Flow of project:

Step 1: Extract license plates from the images. <br/>
Step 2: Preprocessing <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Noise Reduction <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Binarization <br/>
Step 3: Optical Character Segmentation using Google Tesseract

### Number Plates Extraction<br/>
-> urllib library in Python is used to open the image urls from the parsed json file.<br/>
-> The coordinates in the json file are used to crop the vehicle number plates and are saved.<br/>
