# Air-Draw

This Virtual Paint Application allows users to draw on a digital canvas using hand gestures. 

It uses **Mediapipe** for hand tracking and **OpenCV** for image processing. 

Users can select different colors, draw using their index finger, and clear the canvas with a simple gesture.

## Features
- **Hand Tracking**: Tracks the user's hand using Mediapipe's Hand Landmark Detection.
- **Gesture-based Drawing**: The index finger acts as a virtual brush for drawing on the screen.
- **Color Selection**: Choose from four colors (Blue, Green, Red, Yellow).
- **Clear Canvas**: A clear button resets the canvas.
- **Real-time Drawing**: Draw in real-time using webcam input.

## Requirements
Ensure you have the following installed:
- Python 3.7 or higher
- OpenCV (`opencv-python`)
- Mediapipe
- NumPy

Install dependencies using:
```bash
pip install opencv-python mediapipe numpy
```

## How to Run
1. Clone the repository or copy the source code.
2. Run the Python script using:
```bash
python virtual_paint.py
```
3. Allow camera access when prompted.
4. Use hand gestures to select colors and start drawing.

## Instructions
- **Select Colors**: Place your index finger over a color button (Blue, Green, Red, Yellow) to select it.
- **Draw**: Move your index finger over the canvas to draw.
- **Clear Canvas**: Place your index finger over the `CLEAR` button to reset the canvas.
- **Lift Brush**: Pinch the thumb and index finger to stop drawing.
- **Quit**: Press `q` to exit the application.

## File Structure
```bash
- virtual_paint.py   # Main Python script
- README.md          # Project documentation
```


## Future Improvements
- Add an eraser tool.
- Provide more color options.
- Implement gesture-based undo functionality.


