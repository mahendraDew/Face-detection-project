# Simple Face Recognition System using OpenCV

## Overview

This is a simple face recognition system implemented using the OpenCV library in Python. The project involves capturing and saving face images, training a face recognition model, and performing recognition tasks.

## The 3 Phases
To create a complete project on Face Recognition, we must work on 3 very distinct phases:

- Face Detection and Data Gathering
- Train the Recognizer
- Face Recognition

## Features

- **Face Capture:** Capture and save face images with user ID and name.
- **Training:** Train a face recognition model using the LBPH algorithm.
- **Recognition:** Recognize faces in real-time using the trained model.

## Prerequisites

- Python 3.x
- OpenCV (cv2)
- NumPy

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/face-recognition-system.git
    cd face-recognition-system
    ```

2. **Install Dependencies:**

    ```bash
    pip install opencv-python numpy
    ```

3. **Run the Data Gathering Script:**

    ```bash
    python 01_face_dataset.py
    ```

4. **Run the Face Training Script:**

    ```bash
    python 02_face_training.py
    ```

5. **Run the Face Recognition Script:**

    ```bash
    python 03_face_recognition.py
    ```

## Project Structure

- `01_face_dataset.py`: Script for capturing and saving face images with its inputed ids and names.
- `02_face_training.py`: Script for training a face recognition model.
- `03_face_recognition.py`: Script for recognizing faces in real-time.

## Usage

- Follow the instructions in each script to perform face capture, training, and recognition tasks.
- Make sure to provide valid user ID and name during face capture.

## Acknowledgments

This project is a part of my college minor project for the final year. I would like to express my gratitude to VEC, Ambikapur for providing me with the opportunity to work on this project and explore the field of computer vision. Special thanks to Dr. Mohan Rao Mamdikar sir for their guidance and support throughout the development of this face recognition system.

If you find this project useful or would like to contribute, feel free to get in touch or submit a pull request. Your feedback and contributions are highly appreciated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
