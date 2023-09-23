# AI-Virtual-Painter-using-Raspberry-Pi

This is a project that uses OpenCV and MediaPipe to create a virtual painting application that can be controlled by hand gestures. The project uses a Raspberry Pi as the hardware platform and a Pi Camera as the input device.

## Features

- The application can detect the hand landmarks and gestures using MediaPipe.
- The application can draw different shapes and colors on the screen using OpenCV.
- The application can erase the drawing by clicking on the clear button.
- The application can save the drawing as an image file.

## Requirements

- Raspberry Pi 4 Model B (or higher)
- Pi Camera Module V2 (or compatible)
- Python 3.7 (or higher)
- OpenCV 4.5.3 (or higher)
- MediaPipe 0.8.8 (or higher)

## Installation

- Connect the Pi Camera to the Raspberry Pi and enable it in the settings.
- Clone this repository to your Raspberry Pi using the command:

    ```bash
    git clone https://github.com/Mochoye/AI-Virtual-Painter-using-Raspberry-Pi.git
    ```

- Install the required packages using the command:

    ```bash
    pip install mediapipe opencv-python
    ```

## Usage

- Run the main script using the command:

    ```bash
    python Canvas.py
    ```

- Place your hand in front of the camera and make a fist gesture to start drawing.
- Move your hand around to draw on the screen.
- Erase the drawing by clicking on clear button.
- Save the drawing by showing a thumbs up gesture.


## Feedback

If you have any feedback or questions about this project, you can leave a comment on the discussion page.
