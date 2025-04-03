## Features
- **Transfer Learning**: Uses pre-trained ResNet50 with custom classification head
- **Data Augmentation**: Improves generalization with rotation, flipping, and shifts
- **Metrics**: Accuracy, Precision/Recall, F1-Score, ROC-AUC
- **Visualization**: Training curves and confusion matrix

## Requirements
- Python 3.8+
- TensorFlow 2.10+
- numpy
- matplotlib
- split-folders
- scikit-learn
- seaborn
- jupyter

## Model Architecture
- ResNet50 Base → GlobalAveragePooling2D → Dense(256, ReLU) → Dropout(0.5) → Dense(1, Sigmoid)
