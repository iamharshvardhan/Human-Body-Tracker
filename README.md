# Workout Tracker with MediaPipe, OpenCV, and NumPy

## Overview

This project utilizes the MediaPipe library, OpenCV (cv2), and NumPy to track landmarks on the human body, such as joints, hands, legs, and angles between joints. The goal is to create a workout tracker that monitors specific exercises, such as bicep curls and squats, and counts the number of repetitions for both the right and left sides.

## Dependencies

Make sure you have the following libraries installed:

- MediaPipe
- OpenCV (cv2)
- NumPy

You can install these dependencies using the following:

```bash
pip install mediapipe opencv-python numpy
```

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/iamharshvardhan/Human-Body-Tracker.git
```

2. Run the script:

```bash
run the cells in "MediaPipe-Workout-Detection.ipynb"
```

3. Follow the on-screen instructions to calibrate the system and choose the workout mode.

4. Perform the specified workout, and the system will track and count your repetitions.

## Features

### Landmark Tracking

The project uses MediaPipe to detect and track 33 different landmarks on the human body, including joints, hands, and legs.

### Exercise Detection

The system is capable of detecting specific exercises, such as bicep curls and leg squats, based on the positions of landmarks.

### Repetition Counting

Using the tracked landmarks, the system counts the number of repetitions for both the right and left sides of the body during the specified exercises.

### Real-time Feedback

The user receives real-time feedback on their performance, including the current exercise being tracked and the number of repetitions completed.

## Contribution Guidelines

All the meaning full contributions are welcome. Feel free to clone this repo and contribute the best you can.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

Feel free to adapt and extend this project according to your needs. Happy coding!
