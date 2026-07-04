# RetroRebirth

AI-powered photo restoration system that restores photographic negatives and colorizes black-and-white images using deep learning.

---

## Features

- Negative → Positive image restoration
- Black & White image colorization
- Synthetic dataset generation
- U-Net based restoration model
- Interactive Google Colab interface
- Image download support

---

## Technologies

- Python
- PyTorch
- OpenCV
- NumPy
- ModelScope
- DDColor
- Google Colab

---

## Project Workflow

1. Generate synthetic negative-positive image pairs.
2. Train a lightweight U-Net model.
3. Restore photographic negatives.
4. Colorize grayscale images using DDColor.
5. Display original and restored images.

---

## Model

Negative restoration model:
- Architecture: U-Net
- Loss Function: MSE Loss
- Optimizer: Adam
- Epochs: 8
- Image Size: 256×256
- Synthetic Training Images: 2200

---

## Results

The model successfully restores:

- Photographic negatives
- Black-and-white photographs

using deep learning-based restoration techniques.

---

## How to Run

Open the notebook in Google Colab.

Run the cells sequentially:

1. Install dependencies
2. Generate dataset
3. Train model
4. Launch the interface
5. Upload an image
6. Select the restoration mode
7. Download the result

---

## Author

Vidya K T
