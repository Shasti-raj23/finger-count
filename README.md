# finger-count
Creating a project to count the number of fingers raised on a camera and controlling lights based on the count is an exciting and educational endeavor, especially for beginners in electronics and programming.
**Hardware Components:**
Camera: You'll need a camera module capable of capturing images or video. A Raspberry Pi camera or a USB webcam can be suitable options.
Microcontroller or Single Board Computer: A microcontroller like Arduino  be used to process the camera input and control the lights.
LEDs: Choose LEDs to represent each finger count. You'll need at least 5 LEDs for representing counts from 0 to 5.
Resistors: Use appropriate resistors to limit the current flowing through the LEDs.
Breadboard/Jumper Wires: For prototyping and connecting the components.
**Software Components:**
Image Processing Library: Image processing library like open cv for image processing the video.
mediapipe: mediapipe for hand detection and tracking(finger-count.py).
Programming language that is compatible with Ardunio (pyfirmata-controller.py).
**Usage**
Run the main script (e.g., finger_count.py) on your microcontroller/single-board computer.
Raise your hand in front of the camera.
MediaPipe will detect and track your hand, and the system will count the number of fingers raised, controlling the LEDs accordingly.
