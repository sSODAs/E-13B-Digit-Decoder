# E-13B Digit Decoder
<img src="raw/FinalDIP67.bmp" width="400">
(Digital Image Processing course final event)

This digit recognition project focuses on using **basic image processing techniques** to read a six-digit number written in the **E-13B** font from an image. The goal is to practice and demonstrate core concepts such as preprocessing, segmentation, and template matching without using external computer vision libraries.

## What This Project Does
- Reads an input image containing a six-digit E-13B number
- Converts the image to grayscale and binary form
- Segments each digit region
- Matches each digit with predefined templates
- Outputs the recognized number

This is a **rule-based / classical image processing approach**, not a machine learning model.

## Setup and Run
**Requirements**
- Java JDK 8 or higher

**Compile and Execute**
```base
$ javac -d ./build ./src/Final_Event.java
$ java -cp ./build Final_Event
```

## Input & Output
**Input:**<br>
An image containing a six-digit number written in E-13B font.

**Output:**<br>
The decoded number displayed in the console/terminals. Intermediate processing results will saved in the ```output/``` folder.

<br>

## Notes 
This project was created to better understand how **image processing works at a low level**, including how digits can be extracted and recognized using simple algorithms rather than learning-based methods.




