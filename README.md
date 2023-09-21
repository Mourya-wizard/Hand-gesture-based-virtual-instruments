# Hand Gesture Based Virtual Instrument

This is a hand gesture-based virtual instrument created using OpenCV, MediaPipe, and other libraries. With this application, you can interact with your computer using hand gestures to play different musical notes or trigger various sound effects. This README file will guide you through the project and help you get started.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This virtual instrument uses computer vision techniques to recognize hand gestures and translates them into musical notes or sound effects. It leverages the following libraries and tools:

- OpenCV: An open-source computer vision library.
- MediaPipe: A framework for building multimodal (e.g., camera and hand tracking) applied machine learning pipelines.
- Playsound: A library to play sound files.
- Custom Machine Learning Models: Trained models for classifying hand gestures and finger gestures.

## Prerequisites

Before you can use this virtual instrument, you need to have the following installed on your system:

- Python (3.7 or higher)
- OpenCV
- MediaPipe
- Playsound
- Custom machine learning models (provided separately or trained using your data)

## Installation

1. Clone or download this repository to your local machine.

```bash
git clone https://github.com/your_username/hand-gesture-virtual-instrument.git
cd hand-gesture-virtual-instrument
```

2. Install the required Python libraries using pip.

```bash
pip install -r requirements.txt
```

3. Place your custom machine learning models (if any) in the appropriate directories.

## Usage

1. Run the `hand_gesture_virtual_instrument.py` script.

```bash
python app.py
```

2. The application will use your computer's camera to detect your hand gestures.

3. Interact with the virtual instrument by performing various hand gestures. The application will recognize these gestures and trigger corresponding sound effects or musical notes.

4. Press the 'ESC' key to exit the application.

## Customization

You can customize this virtual instrument in the following ways:

- **Add More Gestures**: You can add additional hand gestures and their corresponding sound effects by updating the `gesture_sound_dict` dictionary in the code.

- **Train Custom Models**: If you want to recognize specific gestures, you can train your own custom machine learning models and replace the existing models.

- **Modify Key Bindings**: You can modify the key bindings for different modes or actions by updating the `select_mode` function.

## Contributing

Contributions to this project are welcome. If you have any improvements, bug fixes, or new features to add, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
