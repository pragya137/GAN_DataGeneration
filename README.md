# GST Fraud Detection using cGAN
This notebook uses a Conditional GAN (cGAN) to address class imbalance in a GST fraud detection dataset. The model generates synthetic data for the minority class (fraud cases) to improve classification performance.

## File Description
GAN_dataGeneration.ipynb: Jupyter Notebook containing the implementation of the cGAN model. It includes building the generator and discriminator networks, training the model, and generating new fraud samples.

## Purpose
The main goal is to increase the number of fraudulent cases (class 1) to tackle the class imbalance problem in the dataset.
