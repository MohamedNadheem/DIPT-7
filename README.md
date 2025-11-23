# Edge-Linking-using-Hough-Transformm
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

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="1101" height="324" alt="image" src="https://github.com/user-attachments/assets/fb512c36-7ba7-4481-8a8f-35d507e77bd7" />

### Canny Edge detector output
<img width="1086" height="326" alt="image" src="https://github.com/user-attachments/assets/20a6778b-87dc-4d0c-b9e5-2c90d1537974" />

### Display the result of Hough transform
<img width="1099" height="671" alt="image" src="https://github.com/user-attachments/assets/b4ff1a13-b1e2-41ec-bd5d-943a3ce3a3c1" />
