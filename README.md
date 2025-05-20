# Touch-Free-Digital-Canvas

# Color Marker Paint Application

This project is a real-time virtual paint application that uses a webcam to detect colored markers and allows you to draw on a digital canvas by moving the marker in front of the camera. It uses OpenCV for video processing and color detection.

## Features
- Real-time color detection using HSV color space with adjustable trackbars for fine-tuning color ranges.
- Multiple color options: Blue, Green, Red, Yellow.
- Clear canvas button.
- Drawing directly on a virtual canvas and live camera feed.
- Simple and intuitive GUI with color buttons.

## How to Use
1. Run the Python script.
2. Use the trackbars in the "Color detectors" window to adjust the HSV range for the marker color you want to use.
3. Use the color buttons at the top of the webcam feed window to switch between drawing colors.
4. Move your colored marker in front of the camera to draw on the canvas.
5. Press "CLEAR ALL" to erase the canvas.
6. Press `q` to quit the application.

## Requirements
- Python 3.x
- OpenCV
- NumPy

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Color-Marker-Paint.git
   cd Color-Marker-Paint
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run
bash
Copy
Edit
python paint_app.py
Replace paint_app.py with your script filename if different.

Screenshots

License
This project is licensed under the MIT License.
