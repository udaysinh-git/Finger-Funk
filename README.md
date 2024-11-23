# Finger-Funk: Your Hands, Your Canvas

Virtual canvas—all through the motion of your hands, captured by your webcam.

## 🎨🖐️ Draw with Your Hands: A Gesture-Based Drawing App

Welcome to Finger-Funk! This fun and interactive application allows you to draw on your screen using hand gestures detected by your webcam. Powered by OpenCV and MediaPipe, this project turns your hand movements into digital art.

## Features

- **Hand Gesture Detection**: Uses MediaPipe to detect hand landmarks.
- **Drawing with Fingers**: Draw lines by bringing your thumb and index finger close together.
- **Color Selection**: Change drawing colors by hovering over color boxes.
- **Dynamic Thickness**: Adjust line thickness based on the number of fingers touching the thumb.
- **Erase Mode**: Erase parts of your drawing by spreading your thumb and pinky finger apart.
- **Clear Screen**: Clear the entire drawing by raising the middle finger on both hands.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/udaysinh-git/finger-funk.git
   cd finger-funk
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook main.ipynb
   ```

2. **Follow the instructions in the notebook to start the application.**

## How It Works

- **Hand Detection**: The application uses MediaPipe to detect hand landmarks in real-time.
- **Drawing**: When the thumb and index finger are close together, the application starts drawing lines.
- **Color Selection**: Hover over the color boxes at the top left corner to change the drawing color.
- **Erase Mode**: Spread your thumb and pinky finger apart to erase parts of the drawing.
- **Clear Screen**: Raise the middle finger on both hands to clear the entire screen.

## Dependencies

- OpenCV
- MediaPipe
- NumPy

## Contributing

Feel free to fork this repository and contribute by submitting pull requests. Any improvements or new features are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)

Enjoy drawing with your hands! 🎨🖐️

---

*Note: This project is intended for fun and educational purposes. Please ensure you have a working webcam and a well-lit environment for the best experience.*
