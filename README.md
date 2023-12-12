# Image Classification with VGG-16 and Resnet-50

## Overview
This repository demonstrates image classification using the VGG-16 and Resnet-50 architectures on two diverse datasets: MNIST and Flowers. The project encompasses both training models from scratch and leveraging pre-trained models from ImageNet for transfer learning. The focus is on achieving accurate classification results and understanding the impact of using pre-trained models.

## Key Features
1. **Datasets:**
   - MNIST dataset: Handwritten digit images.
   - Flowers dataset: Collection of flower images.

2. **Pre-processing:**
   - Applies relevant pre-processing techniques to analyze and prepare the datasets for classification.

3. **Model Implementation:**
   - Implements two models from scratch for both VGG-16 and Resnet-50 architectures.
   - Utilizes transfer learning by fine-tuning pre-trained VGG-16 and Resnet-50 models on the ImageNet dataset for enhanced performance.

4. **Evaluation Metrics:**
   - Generates confusion matrices for testing samples on both custom and pre-trained models.
   - Calculates precision, recall, and F1 score to assess model performance.

5. **Results Commentary:**
   - Explores and comments on the results obtained from custom and pre-trained models.
   - Analyzes the impact of transfer learning on classification accuracy and training efficiency.
