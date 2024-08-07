# Face Emotion Detection

This project implements a face expression detection system using machine learning techniques. It can identify various facial expressions in images or real-time video streams.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Features

- Detect faces in images and video streams
- Classify facial expressions into categories (e.g., happy, sad, angry, surprised)
- Real-time processing capability
- Easy-to-use command-line interface
- Pre-trained model included

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/harsh6045/facial-emotion-detection.git
   cd face-emotion-detection
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. To detect expressions in an image:
   ```
   python realtimedetection.py --image path/to/your/image.jpg
   ```

2. To run real-time detection using your webcam:
   ```
   python realtimedetection.py --webcam
   ```

3. For additional options:
   ```
   python realtimedetection.py --help
   ```

## Dataset

We used the FER2013 dataset for training and evaluation. This dataset contains 48x48 pixel grayscale images of faces, categorized into 7 emotions:

0. Angry
1. Disgust
2. Fear
3. Happy
4. Sad
5. Surprise
6. Neutral

## Training

To train the model on your own dataset or fine-tune the existing model:

1. Prepare your dataset
2. Run the training script

## Evaluation

Model performance metrics on the test set:

- Accuracy: 52.2%
- F1-Score: 0.63

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
