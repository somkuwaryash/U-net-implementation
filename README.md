# Brain Tumor MRI Detection using Deep Learning

This repository contains a deep learning-based approach to detect brain tumors from MRI scans. The model was trained and validated on a Kaggle dataset and achieves an accuracy of approximately 94.27%.

## Dataset

The dataset consists of MRI scans of patients' brains categorized into four classes:

- Glioma
- Meningioma
- No tumor
- Pituitary

### Dataset Structure:


brain-tumor-mri-dataset
│
├── Testing
│   ├── glioma
│   ├── meningioma
│   ├── notumor
│   └── pituitary
│
└── Training
    ├── glioma
    ├── meningioma
    ├── notumor
    └── pituitary


## Model

The model used is a custom convolutional neural network (CNN) designed for the classification task.

## Evaluation Metrics

The model was evaluated based on its accuracy, sensitivity, and specificity for each class:

- **Accuracy on the test set**: 94.27917620137299%
  
- **Sensitivity and Specificity**:
  - Glioma: 
    - Sensitivity: 0.8400
    - Specificity: 0.9860
  - Meningioma: 
    - Sensitivity: 0.9248
    - Specificity: 0.9520
  - No tumor: 
    - Sensitivity: 0.9951
    - Specificity: 0.9928
  - Pituitary: 
    - Sensitivity: 0.9933
    - Specificity: 0.9926

## Grad-CAM Visualization

The Grad-CAM visualization technique was used to understand which parts of the MRI scans the model focuses on while making predictions. This can be useful for understanding model decisions and ensuring that the model focuses on relevant features.

## Getting Started

1. Clone this repository.
2. Install the necessary Python packages.
3. Run the Jupyter notebook to train the model and evaluate its performance.

## Dependencies

- Python
- PyTorch
- Torchvision
- PIL
- OpenCV
- Matplotlib

## Credits

- Dataset sourced from Kaggle. 
- Model and analysis by [Your Name].

## License

This project is open-sourced under the MIT License.
