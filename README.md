SAR Image Colorization using GAN
📌 Project Overview

This project focuses on converting grayscale SAR (Synthetic Aperture Radar) satellite images into realistic colorized images using Deep Learning and Generative Adversarial Networks (GANs).

SAR images are difficult to interpret because they contain noise and lack natural color information. This project helps improve visualization and understanding of remote sensing images for applications like agriculture, disaster monitoring, and land analysis.

🚀 Features
SAR Image Colorization using GAN
Deep Learning based image generation
Image preprocessing and normalization
Generator and Discriminator models
Realistic color prediction
Training visualization using epochs and loss graphs
🛠️ Technologies Used
Python
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Google Colab
🧠 Model Used
GAN (Generative Adversarial Network)

GAN consists of two neural networks:

Generator
Generates colorized images from grayscale SAR images.
Discriminator
Checks whether generated images are real or fake.

Both models compete with each other, improving image quality over time.

📂 Dataset
SAR image dataset
Around 28,000 image pairs used for training
Images resized and normalized before training
⚙️ Project Workflow
Collect SAR dataset
Preprocess images
Train GAN model
Generate colorized images
Evaluate output quality
▶️ How to Run Project
Clone Repository
git clone https://github.com/yourusername/SAR-Image-Colorization.git
Install Requirements
pip install -r requirements.txt
Run Project
python train.py
📈 Future Scope
Real-time satellite image colorization
Better GAN architectures like WGAN or CycleGAN
Higher resolution image generation
Integration with GIS systems
