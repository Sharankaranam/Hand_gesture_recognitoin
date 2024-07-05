# Hand Gesture Recognition

This project implements a hand gesture recognition system using OpenCV and the cvzone HandTrackingModule. The code captures images from a webcam, detects hands, crops the region of interest, and saves the processed images for further use.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you need to have Python and the necessary libraries installed. Follow the steps below to set up the environment:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/Hand_gesture_recognition.git
    cd Hand_gesture_recognition
    ```

2. **Create a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

After setting up the environment, you can run the hand gesture recognition script:

1. **Run the script:**

    ```bash
    python hand_gesture_recognition.py
    ```

2. **Interact with the script:**

    - The webcam will start capturing video.
    - When a hand is detected, it will be cropped and displayed.
    - Press the `s` key to save the cropped hand image to the `Data/DOT` folder.

## Project Structure




## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request. Follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -m "Add your feature"
    ```

4. **Push to the branch:**

    ```bash
    git push origin feature/your-feature-name
    ```

5. **Open a pull request.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


opencv-python
cvzone
numpy
