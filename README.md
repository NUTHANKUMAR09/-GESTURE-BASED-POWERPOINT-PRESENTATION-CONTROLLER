# Hand Gesture Controlled Presentation

This Python script allows you to control a presentation using hand gestures detected by your webcam. It uses OpenCV and the `cvzone` library for hand tracking and gesture recognition.

## Features

* **Slide Navigation:**
    * Move to the previous slide by raising your left hand (index finger up).
    * Move to the next slide by raising your right hand (little finger up).
* **Drawing:**
    * Draw on the slides using your index finger.
    * Start a new drawing line when your index finger is up.
    * Place a dot when your index and middle fingers are up.
    * Delete the last drawing when index, middle and ring finger are up.
* **Real-time Camera Overlay:**
    * Displays a small camera feed in the top-right corner of the presentation.

## Prerequisites

* Python 3.x
* OpenCV (`cv2`)
* `cvzone`
* `numpy`

You can install the required libraries using pip:

```bash
pip install opencv-python cvzone numpy
python your_script_name.py
