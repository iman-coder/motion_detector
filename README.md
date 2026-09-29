# Motion Detection Camera

A simple Python script that monitors a webcam for motion and records detected activity as timestamped `.avi` video files.

## Requirements

- Python 3
- OpenCV for Python
- Windows, because the script imports `winsound`
- A connected webcam

Install OpenCV:

```bash
python -m pip install opencv-python
```

## Run

From this folder, run:

```bash
python camera.py
```

The script opens the webcam and saves recordings in this folder as `motion_<timestamp>.avi`. Press `q` in the camera window to stop.

Generated recordings are excluded from Git by `.gitignore`.
