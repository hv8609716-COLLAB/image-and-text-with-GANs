# image-and-text-with-GANs

# Handwritten Digit Generation using GAN (TensorFlow)

This project uses a **Generative Adversarial Network (GAN)** built with **TensorFlow** to generate AI-created handwritten digit images.

The model is trained on the **MNIST dataset** and generates new handwritten-style digits after training.

---

## Features

* GAN architecture
* Generator + Discriminator
* Uses MNIST handwritten dataset
* Fast training mode
* Generates handwritten digit images
* TensorFlow implementation

---

## Tech Stack

* Python
* TensorFlow
* NumPy
* Matplotlib

---

## How GAN Works

### Generator

Creates fake handwritten images from random noise.

### Discriminator

Tries to detect whether an image is real or AI-generated.

### Training

Both networks improve together until generated digits become realistic.

---

## Project Structure

```text id="nhm8k6"
project/
│
├── gan.py
├── README.md
├── requirements.txt
└── generated_output.png
```

---

## Installation

Clone repository:

```bash id="jlwmo1"
git clone YOUR_REPOSITORY_LINK
```

Open folder:

```bash id="0u8z9v"
cd YOUR_PROJECT
```

Install packages:

```bash id="4t8xxm"
pip install tensorflow numpy matplotlib
```

---

## Run Project

Execute:

```bash id="s3v6nh"
python gan.py
```

---

## Dataset

Dataset used:

```text id="2frbim"
MNIST Handwritten Digits
```

Image size:

```text id="jv6x6m"
28 × 28 grayscale
```

Fast training configuration:

```text id="0hnd1t"
Samples: 5000
Epochs: 2
Batches: 20
```

---

## Model Architecture

### Generator

```text id="ggqmcj"
Dense
→ LeakyReLU
→ Reshape
→ Conv2DTranspose
→ Conv2DTranspose
→ Output Image
```

### Discriminator

```text id="f4q9n9"
Conv2D
→ LeakyReLU
→ Flatten
→ Dense
```

---

## Example Output

```text id="g3c9rk"
Training Complete
Generated Text:
AI generated handwritten digit
```

Generated image:

```text id="i3oh2g"
(Displays a generated handwritten digit)
```

---

## Future Improvements

* Train more epochs
* Generate higher quality digits
* Conditional GAN
* Web interface using FastAPI
* Save generated outputs automatically

---

## Learning Outcome

This project demonstrates:

* Deep Learning
* GAN Architecture
* Image Generation
* TensorFlow Training Pipeline

---

## Author

Harsh Vardhan
