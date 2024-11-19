# Image Classification: SVM and CNN

[![image.png](https://i.postimg.cc/1tmx3wHQ/image.png)](https://postimg.cc/5HRKPHT7)

This repository demonstrates a workflow for image classification using **SVM (Support Vector Machine)** and **CNN (Convolutional Neural Network)**. It includes loading and preprocessing grayscale images, training both models, and comparing their predictions.

---

## Features
1. **Preprocessing**: Convert images to grayscale, resize, normalize, and prepare for model training.
2. **SVM Classifier**: Train and evaluate an SVM model for binary classification.
3. **CNN Classifier**: Build, train, and evaluate a CNN model for binary classification.
4. **Comparison**: Predict using both SVM and CNN, displaying results with the original image.

---

## Steps to Run
1. Install dependencies:
   ```bash
   pip install numpy scikit-image scikit-learn tqdm tensorflow matplotlib
   ```
2. Place your dataset in the `./train/` directory, organized in subfolders (e.g., `cat`, `dog`).
3. Run the script:
   ```bash
   python classify_images.py
   ```

---

## Key Libraries Used
- **NumPy**: Efficient numerical computations.
- **scikit-image**: Image processing utilities.
- **scikit-learn**: SVM classifier and evaluation metrics.
- **TensorFlow/Keras**: CNN model definition and training.
- **Matplotlib**: Visualization of results.

---

## Model Comparison
- **SVM**: Works well with low-dimensional feature vectors.
- **CNN**: Provides higher accuracy for image data with spatial hierarchies.

---

## Example Results
After training, the models predict whether an image is of a **Cat** or **Dog**, visualizing the predictions.
[![image.png](https://i.postimg.cc/ZR21F2mT/image.png)](https://postimg.cc/BL5YJhty)
[![image.png](https://i.postimg.cc/MT8JrvkD/image.png)](https://postimg.cc/941kDXQR)
[![image.png](https://i.postimg.cc/7bvmfyk2/image.png)](https://postimg.cc/y3PFbtW1)
---

Feel free to fork and adapt! 🚀  
**Author**: Marjana Begum
[Get Dataset from here](https://drive.google.com/file/d/1hiImLFBEDb5NjU9AfdAnx-4SQDK_QEHR/view?usp=sharing)
