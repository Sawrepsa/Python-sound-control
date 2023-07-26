# Hand Gesture Controlled Sound Level

This project allows controlling the device's sound level using hand gesture recognition. The project is built using Python and the following libraries to achieve sound control.

## Used Libraries
To run the project files, you need to install the following libraries:

- **cv2 (OpenCV)**: Used for image processing and camera access.
- **Mediapipe**: A powerful library used for hand gesture recognition.
- **math**: Used for mathematical operations.
- **ctypes**: Provides interaction with low-level C languages.
- **comtypes**: Used for sound control through the Windows API.
- **pycaw.pycaw**: Enables interaction with sound devices in Windows.
- **numpy**: Used for arrays and mathematical operations.

## Usage
- Download or clone the project files to your computer.

- Run the **python-sound-control.py** file in the main directory.

- When the program starts, the camera screen will open, and you should show your hand in front of the camera.

- When your hand is detected, the sound level will be adjusted based on the hand's height. As the hand's height increases, the sound level will also increase, and as the hand's height decreases, the sound level will decrease.

## How It Works?
The project performs hand gesture recognition using the Mediapipe library.
Based on the hand coordinates, it determines the hand's height and adjusts the sound level accordingly.
For sound control, it utilizes the ctypes and pycaw.pycaw libraries.

## Contributing
This project is open-source, and we welcome contributions! Please submit pull requests for bug fixes or new features.

## Acknowledgments
This project leverages the powerful Mediapipe library for hand gesture recognition. We thank the Mediapipe team for their contribution.
For sound control, we use the ctypes and pycaw.pycaw libraries. We extend our appreciation to the developers of these libraries.

## Contact
If you have any questions or suggestions, please feel free to contact us via email: sawrepsa@gmail.com

