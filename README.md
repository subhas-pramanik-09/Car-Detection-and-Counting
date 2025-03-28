# Car Counting from Video

This project counts the number of cars passing through a designated line in a video file using OpenCV and background subtraction techniques.

## Features
- Detects and counts vehicles crossing a predefined line.
- Uses background subtraction for motion detection.
- Implements morphological transformations for noise reduction.
- Displays real-time video with detected vehicles and count overlay.

## Requirements
Ensure you have the following installed:
- Python 3.x.x
- OpenCV (`cv2`)
- NumPy (`numpy`)

You can install the dependencies using:
```bash
pip install opencv-python numpy
```

## How It Works
1. Loads the video file (`video.mp4`).
2. Applies background subtraction to detect moving objects.
3. Filters out noise using Gaussian blur and morphological operations.
4. Draws bounding boxes around detected vehicles.
5. Counts a vehicle when it crosses the predefined counting line.
6. Displays the total vehicle count on the screen.

## Usage
1. Place a video file named `video.mp4` in the same directory as the script.
2. Run the script:
   ```bash
   python car_count.py
   ```
3. The video will display with detected vehicles and a count overlay.
4. Press `Enter` to exit the program.



