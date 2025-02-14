# Cancer Cell Detection using Deep Learning

This project uses CNN to detect cancerous cells in images.

## Dataset
- The dataset consists of images categorized into `Benign` and `Malignant`.
- Training images are stored in `train/0` (Benign) and `train/1` (Malignant).
- Test images are stored in `test/`.

## Model
- CNN with Conv2D, MaxPooling, Flatten, and Dense layers.
- Trained using `binary_crossentropy` loss and Adam optimizer.
- Achieved high accuracy.

## Installation
To install dependencies:
```bash
pip install -r requirements.txt
