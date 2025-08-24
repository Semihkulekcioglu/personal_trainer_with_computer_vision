# Personal Trainer

[Türkçe](README_TR.md) | [English](README.md)

A computer vision application that tracks exercise movements and counts repetitions in real-time. The project uses MediaPipe and OpenCV to detect body positions and count exercises.

## Features

- Real-time body position detection
- Push-up counting
- Angle calculation and visualization
- Webcam and video file support

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## Installation

1. Clone the project:
```bash
git clone https://github.com/Semihkulekcioglu/personal_trainer_with_computer_vision.git
cd personal_trainer_with_computer_vision
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the program:
```bash
python "Kisisel_antrenor(Personal Trainer).py"
```

2. For webcam usage, run the code as is.
3. To use with a video file, modify this line in the code:
```python
cap = cv2.VideoCapture("your_video_file.mp4")
```

## Example Outputs

<img width="640" height="640" alt="Output_3" src="https://github.com/user-attachments/assets/3fdbdf14-5955-46f8-8435-061575437956" />

Example outputs can be found in the Results folder.

## Features in Detail

- **Real-time Body Tracking**: Uses MediaPipe's pose detection to track 33 body landmarks
- **Exercise Counting**: Automatically counts push-ups based on arm angle
- **Visual Feedback**: Draws body landmarks and connections in real-time
- **Angle Measurement**: Calculates and displays joint angles during exercises

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
