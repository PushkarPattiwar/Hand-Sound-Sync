## Hand Sound Sync Project

### Overview:
Hand Sound Sync is a Python project aimed at controlling the volume of your computer's audio output by using hand gestures captured through your webcam. The project utilizes the Mediapipe library for hand detection and tracking, and the Pycaw library to access and control the audio output volume.

### Requirements:
- Python 3.x
- OpenCV (`cv2`)
- Mediapipe (`mediapipe`)
- Pycaw (`pycaw`)

### Installation:
1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install opencv-python mediapipe pycaw
   ```

**Usage:**
1. Run the `Hand_Sound_Sync.py` script.
2. Ensure your webcam is properly connected and functioning.
3. Position your hand in front of the webcam.
4. Adjust the volume by moving your thumb and index finger closer or farther apart:
   - Bring your thumb and index finger closer together to decrease the volume.
   - Spread your thumb and index finger apart to increase the volume.
5. Press the spacebar to exit the program.

**Implementation Details:**
- The project captures video input from the webcam and detects hand landmarks using the Mediapipe library.
- It tracks the positions of the thumb and index finger to determine the desired volume level.
- The volume control functionality is achieved through the Pycaw library, allowing for the adjustment of the system's audio output volume.
- A graphical representation of the current volume level is displayed on the screen as a vertical bar, along with the corresponding percentage.
- The program stops when the spacebar key is pressed.
