# GAN Training with TensorFlow and Keras

This project demonstrates the implementation and training of a **Generative Adversarial Network (GAN)** using TensorFlow and Keras. The project includes:

- A **Generator** model that creates images from random noise.
- A **Discriminator** model that distinguishes real images from generated ones.
- Utilities for saving intermediate results and training checkpoints.

---

## Features
- **GAN Architecture**: Implementation of both generator and discriminator models.
- **Training Loop**: Custom training with label smoothing and checkpointing.
- **Image Generation**: Periodically saves generated images during training.
- **Requirements**: Pre-configured with necessary dependencies for compatibility.

---

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/<your-username>/<repository-name>.git
   cd <repository-name>
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

---

## Usage

### Training the GAN
1. Run the training script:
   \`\`\`bash
   python train_gan.py
   \`\`\`
   Replace \`train_gan.py\` with the name of your training script.

2. Generated images will be saved periodically in the \`image_gen\` directory.

### View Generated Images
   Generated images are saved in \`.png\` format:
   \`\`\`
   image_gen/epoch_<epoch_number>.png
   \`\`\`

---

## File Structure
\`\`\`
project/
│
├── train_gan.py         # Main script for training the GAN
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── image_gen/           # Directory for generated images
└── models/              # Directory for saved model checkpoints
\`\`\`

---

## Dependencies
The required libraries are listed in \`requirements.txt\`. Install them with:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

---

## Example Output
Sample generated image after training for a few epochs:

![Sample Output](image_gen/epoch_100.png)

---

## Contributing
Contributions are welcome! Fork the repository, make your changes, and open a pull request.

---
