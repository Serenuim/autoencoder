# autoencoder

# Convolutional Autoencoder with TensorFlow/Keras

This project implements a **Convolutional Autoencoder (ConvAE)** using TensorFlow and Keras to learn efficient encodings of image data and reconstruct input images.

---

## 📌 Project Structure

- **Model:** Convolutional Autoencoder (`ConvAE`)
- **Loss Function:** Mean Squared Error (`mse`)
- **Optimizer:** Adam with learning rate `0.001`
- **Regularization:** Built-in with architecture (e.g., batch norm, dropout if applied)
- **Checkpointing:** Best model is saved using `.keras` format

---

## 📁 Dataset

- Images are loaded using:
  ```python
  tf.keras.preprocessing.image_dataset_from_directory(...)
