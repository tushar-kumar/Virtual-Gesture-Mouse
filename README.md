# Virtual Gesture Mouse using Python

![Demo](demo.gif)

Virtual Gesture Mouse is a Python project that allows you to control your computer's mouse cursor using hand gestures captured through your webcam. This project utilizes the power of OpenCV, Mediapipe, and PyAutoGUI to provide a hands-free and intuitive way of interacting with your computer.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Control mouse cursor movements using hand gestures.
- Click and drag functionality using specific gestures.
- Intuitive and user-friendly interface.
- Adjustable sensitivity and gesture recognition parameters.
- Seamless integration of OpenCV, Mediapipe, and PyAutoGUI.

## Requirements

- Python 3.x
- OpenCV (cv2)
- Mediapipe
- PyAutoGUI

## Installation

1. Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/tushar-kumar/Virtual-Gesture-Mouse.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Virtual-Gesture-Mouse
   ```

3. Install the required libraries using pip:

   ```bash
   pip install opencv-python mediapipe pyautogui
   ```

## Usage

1. Run the `main.py` script:

   ```bash
   python main.py
   ```

2. Position yourself in front of the webcam, ensuring your hand is visible within the frame.

3. Make specific hand gestures to control the mouse cursor:
   - **Cursor Movement**: Move your index finger to control the cursor's direction.
   - **Left Click**: Close your index finger and thumb together.
   - **Right Click**: Close your middle finger and thumb together.
   - **Drag**: Perform a long press gesture with the index finger, then move your hand.

4. Press `Esc` to exit the application.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or a pull request in this repository. Your feedback and contributions will be greatly appreciated.

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Open a pull request describing your changes.

