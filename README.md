# OpenCV Drowsiness Detector using Python and Dlib

This project implements a real-time drowsiness detection system using Python, OpenCV, and Dlib. It aims to enhance driver safety by identifying signs of fatigue or sleepiness and alerting the driver accordingly.

## Features

- **Real-Time Eye Aspect Ratio (EAR) Analysis**: Detects and monitors eye closure duration.
- **Facial Landmark Detection**: Utilizes Dlib's pre-trained models for accurate face and eye region tracking.
- **Audio Alert System**: Triggers an alarm when drowsiness is detected.
- **Configurable Parameters**: Allows customization of thresholds for EAR and drowsiness detection duration.

## Technologies Used

- **Python**: Core programming language.
- **OpenCV**: For real-time image processing and video analysis.
- **Dlib**: For facial landmark detection and EAR calculation.

## Prerequisites

1. **Python** (Version 3.7 or higher)
2. Required Python packages:
   - OpenCV
   - Dlib
   - Numpy
   - Scipy (optional for advanced computations)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/drowziness.git
   cd drowsiness-detector
