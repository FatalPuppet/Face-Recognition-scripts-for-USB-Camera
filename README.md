# Face-Recognition-scripts-for-USB-Camera
I decided to take the original CV + Face Recognition process away from the Raspberry Pi and implant it into a different Linux machine, which will use a separated USB webcam.

There is not much to add to the original project beside that I have removed the "picamera" details and added the instruction to use the actual USB camera.
Both the facial_recognition.py and image_capture.py script have been updated to use the external Camera, with the former allowing for a FullHD resolution to be shown on screen.

The facial_recognition_hardware.py has been updated as well, but since it is lacking the GPIO module of the original Raspberry Pi it is not working (script crash at the required command).

Truth be told I used the help of an external AI system to make the changes.
