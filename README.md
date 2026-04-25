# Plant Disease Classification using ResNet18

## Overview
This project uses transfer learning with ResNet18 to classify plant diseases from leaf images.

## Approach
- Used pretrained ResNet18 and froze convolutional layers
- Replaced final fully connected layer with a custom classifier
- Applied data augmentation (rotation, flipping) to improve generalization

## Dataset
PlantVillage dataset from Kaggle

## Results
- Training Accuracy: 90.60%
- Validation Accuracy: 93.76%

## Tech Stack
- Python
- PyTorch
- torchvision

## Insights
- Validation accuracy exceeded training accuracy due to data augmentation and dropout
- Transfer learning significantly improved performance compared to training from scratch

## Future Improvements
- Fine-tune deeper layers of ResNet
- Deploy model using Flask or FastAPI
