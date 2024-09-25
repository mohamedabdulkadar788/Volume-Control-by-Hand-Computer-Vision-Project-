# Volume-Control-by-Hand-Computer-Vision-Project

This project implements a volume control application using computer vision techniques. It utilizes OpenCV for image processing and MediaPipe for hand tracking, allowing users to control the system volume with hand gestures. The Pycaw library is used for audio control on Windows.

## Features
- **Hand Gesture Recognition**: Utilizes MediaPipe for hand tracking, allowing the application to recognize hand gestures.
- **Volume Control**: Adjusts the system volume based on the distance between the user's thumb and index finger.
- **Visual Feedback**: Displays the current volume level as a percentage and provides a visual representation of the volume bar on the screen.
- **Dynamic Interaction**: The volume adjusts in real time as the user moves their hand, with feedback provided through a changing volume bar and percentage display.
- **Mute Functionality**: The application can detect when the user's fingers are very close (below a certain length threshold) and indicate a mute state visually.
- **FPS Display**: Shows the frames per second (FPS) in real-time to ensure smooth interaction.

## Installation

### Prerequisites
Make sure you have Python 3.x installed on your system.

### Dependencies
You can install the required dependencies using the following command:

`pip install -r requirements.txt`

## Usage

### 1. Clone or Download the repo:
You can either clone the repository or download the zip file.

### 2. Command for git clone:
- `git clone https://github.com/mohamedabdulkadar788/Volume-Control-by-Hand-Computer-Vision-Project-.git`
- `cd Volume-Control-by-Hand-Computer-Vision-Project--main`
- Then run the file.
