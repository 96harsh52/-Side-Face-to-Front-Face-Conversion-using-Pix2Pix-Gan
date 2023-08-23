# Side Face-to-Front Face Generation and Face Recognition

## Introduction
Face detection, recognition, and generation have a wide range of applications in various fields, including security, emotion detection, and attendance tracking. However, existing algorithms may not perform well with side-view images of faces. This project aims to address this issue by generating frontal face images from side-view images using Generative Adversarial Networks (GANs) and enhancing face recognition algorithms to work effectively with images from different angles and poses.


![tt](https://github.com/96harsh52/-Side-Face-to-Front-Face-Conversion-using-Pix2Pix-Gan/assets/36518896/e352c4f7-aa8d-41c1-a397-6cc1eb2b9595)


## Project Overview
The project is divided into the following main components:

1. Front Face and Side Face Detection:
   - Utilizing OpenCV and Haar cascade classifier for face detection.
   - Detecting and processing side-view images to prepare for GAN training.

2. Side Face to Front Face Generation:
   - Implementing a Generative Adversarial Network (GAN) to generate frontal face images.
   - Training the GAN using side-view and corresponding front face images.

3. Face Recognition:
   - Extracting face embeddings from images using deep learning.
   - Training a Support Vector Machine (SVM) for face recognition.
   - Applying face recognition to detect and recognize known faces.
  


![Screenshot 2023-08-23 204132](https://github.com/96harsh52/-Side-Face-to-Front-Face-Conversion-using-Pix2Pix-Gan/assets/36518896/e8e3af91-f162-4bc4-9eff-8f33c8d4ded1)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/side-face-to-front-face.git
   ```

## Usage
1. Prepare your dataset by organizing side-view and front face images into appropriate folders.
2. Preprocess the dataset using the provided `cropFace()` function to extract face regions.
3. Train the GAN using the training script. Adjust hyperparameters as needed.
4. Train the face recognition model using the provided face embeddings and SVM training script.
5. Use the trained models to generate front face images from side-view images and perform face recognition.

## Results
Include examples of generated front face images and demonstrate the face recognition performance using images or videos.

## Dependencies
- OpenCV
- TensorFlow (for GAN)
- Scikit-learn (for SVM)
- Other dependencies listed in requirements.txt

## Contributing
Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.
