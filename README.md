# Retina Vessel Segmentation 🩺🔍


This project focuses on segmenting blood vessels in retinal images using a combination of traditional image processing techniques and deep learning approaches. It includes three main components for preprocessing, feature extraction, and segmentation.

## 📖 About

This repository implements retinal vessel segmentation through:  
- 🖼️ HOG and GMM-based feature extraction for vessel segmentation (Modelleme.ipynb)  
- 🌟 Image enhancement pipelines with a best BRISQUE score of 25.29 (Onisleme.ipynb)  
- 🧠 A UNet deep learning model achieving an IoU of 0.8639 (yapayZeka.ipynb)

## 🚀 Features

- **Traditional Segmentation**: Uses Histogram of Oriented Gradients (HOG) and Gaussian Mixture Models (GMM) to extract and segment retinal vessels.
- **Image Preprocessing**: Applies various pipelines (e.g., CLAHE, Top-Hat, normalization) to enhance retinal images for better segmentation.
- **Deep Learning**: Implements a UNet model for accurate vessel segmentation with high IoU scores.
- **Evaluation Metrics**: Includes IoU for segmentation accuracy and BRISQUE for image quality assessment.

## 📂 Repository Structure

- **Modelleme.ipynb**: Implements HOG and GMM-based segmentation with morphological operations, achieving an average IoU of ~0.54.
- **Onisleme.ipynb**: Provides preprocessing pipelines to enhance retinal images, with the best pipeline scoring a BRISQUE of 25.29.
- **yapayZeka.ipynb**: Trains a UNet model for vessel segmentation, achieving an IoU of 0.8639 on test images.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alperenec/retina-vessel-segmentation.git
   cd retina-vessel-segmentation
