# FaceGuard

**FaceGuard** is an advanced facial authentication system designed to provide secure and seamless user identification through facial recognition technology. Ideal for applications in proctoring, KYC processing, and device security.

## Features

- **Real-time Facial Recognition**: Detect and recognize faces in real-time using a webcam.
- **Secure Authentication**: Match captured faces with known faces to ensure secure access.
- **User-Friendly Interface**: Easy-to-use interface with live video feed and face recognition results.

## Requirements

- Python 3.x
- `face_recognition` library
- `opencv-python` library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Karthikkv1/FaceGuard.git
    cd FaceGuard
    ```

2. Install the required libraries:
    ```bash
    pip install face_recognition opencv-python
    ```

## Usage

1. Prepare a directory named `known_faces` with subdirectories for each person. Each subdirectory should contain images of the corresponding person.

2. Run the script:
    ```bash
    python faceguard.py
    ```

3. The application will open a video window showing real-time facial recognition. Press 'q' to exit.

## Configuration

- **known_faces_dir**: Specify the directory containing known faces. Modify the `known_faces_dir` variable in `faceguard.py` to point to your directory.



## Acknowledgements

- [face_recognition](https://github.com/ageitgey/face_recognition) for facial recognition functionality.
- [OpenCV](https://opencv.org/) for video processing.

