# **EXP NO. 7: Edge-Linking-using-Hough-Transformm**
# **NAME : KRISHNA KUMAR R**
# **REG NO : 212223230107**

## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="686" height="467" alt="image" src="https://github.com/user-attachments/assets/7b479279-5e30-4a60-917f-11e122da1d55" />

<img width="684" height="475" alt="image" src="https://github.com/user-attachments/assets/34a2b165-ca87-440c-a2ad-ea0508e18c5d" />


### Canny Edge detector output
<img width="765" height="487" alt="image" src="https://github.com/user-attachments/assets/1d496b27-baad-40e9-acee-7913df6fde93" />


### Display the result of Hough transform
<img width="738" height="475" alt="image" src="https://github.com/user-attachments/assets/73a051fc-bf65-4b3b-92a7-a5b514a2f707" />

