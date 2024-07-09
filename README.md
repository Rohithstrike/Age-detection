# Age and Gender Detection

Real-time age and gender detection using OpenCV and deep learning models.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Rohithstrike/AgeDetection.git
    cd AgeDetection
    ```

2. **Set up the virtual environment and install dependencies:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

## Usage

1. **Run the age and gender detector:**
    ```bash
    python main.py
    ```

2. **Press 'q' to quit the application.**

## Files

- `main.py`: Main script
- `age_deploy.prototxt`: Age model architecture
- `age_net.caffemodel`: Pre-trained age model
- `gender_deploy.prototxt`: Gender model architecture
- `gender_net.caffemodel`: Pre-trained gender model
- `opencv_face_detector.pbtxt`: Face detection model architecture
- `opencv_face_detector_uint8.pb`: Pre-trained face detection model
- `requirements.txt`: Python dependencies