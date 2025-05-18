# BLIND-ASSISTANCE-SYSTEM-USING---DIGITAL-IMAGE-PROCESSING-MATLAB-
# 🦯 Blind Assistance System using MATLAB & Digital Image Processing

## 📌 Overview

The **Blind Assistance System** is a computer vision-based object detection solution built using MATLAB and AlexNet. It helps visually impaired individuals by detecting and identifying nearby objects from images. The system outputs the detected object as text — enabling enhanced awareness of the surroundings.

📌 **Note:** This version of the system does **not** use a live camera feed or voice output. It focuses on **object detection through static images using the AlexNet model in MATLAB**.

---

## 🎯 Objectives

- Detect and identify common objects using deep learning
- Provide clear and simple text-based output for detected objects
- Lay the foundation for a more advanced assistive tool for the visually impaired

---

## 🧠 Features

- 🧠 Pre-trained **AlexNet CNN** used for object recognition
- 🖼️ Supports classification of images containing everyday objects
- 📝 Outputs object name as plain text
- 💡 Simple and user-friendly MATLAB interface

---

## 🛠️ Technologies Used

| Component        | Description                          |
|------------------|--------------------------------------|
| MATLAB R2021a+   | Development environment              |
| AlexNet          | Pre-trained deep learning model      |
| MATLAB Toolboxes| Deep Learning Toolbox, Image Processing Toolbox |

##  How It Works
1. Load the AlexNet pre-trained model in MATLAB

2 . Input an image manually from the testImages folder

3. The model classifies the image and displays the name of the object in text format

4. The result is printed on the MATLAB command window or displayed using a simple GUI

   ## Sample Output
Input: Image of a car

Output (Text): "Detected Object: car"

Input: Image of a bench

Output (Text): "Detected Object: bench"

## How to Run
1. Install MATLAB (2021a or later recommended)

2. Install required toolboxes:

3. Deep Learning Toolbox

4. Image Processing Toolbox

5. Download and extract the project folder

5. Open classifyObject.m in MATLAB

6. Run the script and select an image from the testImages folder

7. View the classification result in the command window or popup

