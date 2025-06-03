# VirtualMouse

VirtualMouse is a Python-based application that allows users to control their computer mouse using hand gestures captured from a webcam. Utilizing OpenCV and MediaPipe for hand tracking, this project provides a hands-free way to navigate and interact with your computer, making it both innovative and accessible.

## Features

- **Hand Tracking:** Uses your webcam to detect and track hand gestures in real time.
- **Gesture Recognition:** Maps specific gestures to mouse actions such as moving the cursor, clicking, and dragging.
- **No Additional Hardware:** Works with any standard webcam.
- **Customizable:** Easily extend or modify gestures for additional control.

## Demo

![VirtualMouse Demo](demo.gif)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tanishqkumar700/VirtualMouse.git
   cd VirtualMouse
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the main script:**
   ```bash
   python virtual_mouse.py
   ```

2. **Grant webcam access** when prompted.
3. **Control your mouse** with hand gestures as described below.

## Controls

- **Move Cursor:** Move your index finger in front of the webcam.
- **Left Click:** Touch your thumb and index finger together.
- **Right Click:** Touch your thumb and middle finger together (customize in code if needed).
- **Drag:** Hold the left-click gesture while moving your hand.
- **Scroll:** (Optional) Gesture-based scrolling can be added.

> _You can modify or extend gestures in `virtual_mouse.py`._

## Requirements

- Python 3.7+
- OpenCV (`opencv-python`)
- MediaPipe
- PyAutoGUI

Install dependencies using:
```bash
pip install opencv-python mediapipe pyautogui
```

Or use the provided `requirements.txt`.

## File Structure

```
VirtualMouse/
├── virtual_mouse.py      # Main application script
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── demo.gif              # Demo animation (optional)
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)

---

*Created by [tanishqkumar700](https://github.com/tanishqkumar700)*
