# Python-Arduino-Person-Recognition
IT 254 Project 1

Project Steps:

1) train facial recognition model
- Accessed teachable machine at https://teachablemachine.withgoogle.com/train.
- Trained the model to recognize between images showing a human face and images that don't.
- Exported the model in Keras format.

2) Upload Arduino Code:
- Opened the Arduino IDE and uploaded the attached code.
- The attached code should inform the Arduino to light up once the input is provided that a face is being recognized.

3) Set up Arduino Python Connection
- Open Visual Studio Code and input the attached Python code.
- The attached code should reference the Keras model and labels and provide the appropriate input to the Arduino when a face is being seen by the computer camera.

4) Test System
- Close the Arduino IDE.
- Activate the code on Visual Studio Code.
- Everything is working correctly if the camera sees a face and the LED lights up.

Systems used:
- Python 3
- TensorFlow
- Keras
- OpenCV
- PySerial
- Arduino IDE
- Arduino Mega 2560

