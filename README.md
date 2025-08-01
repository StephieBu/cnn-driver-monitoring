# cnn-driver-monitoring
This project applies deep learning for computer vision in a real-world safety context: detecting driver inattention states from images. It involves building a baseline CNN, systematically improving it through hyperparameter tuning, and applying transfer learning with pretrained models (VGG16/ ResNet50/ DenseNet).

## Project Overview
The goal of this project is to classify driver behavior into six categories:
- Dangerous driving  
- Distracted  
- Drinking  
- Safe driving  
- Sleepy driving  
- Yawning  

## Project Focus
The dataset is sourced from **Kaggle:** [Driver Inattention Detection Dataset on Kaggle](https://www.kaggle.com/datasets/zeyad1mashhour/driver-inattention-detection-dataset).
and consists of labeled images covering various driver inattention states, which enables the application of convolutional neural networks and transfer learning models (VGG16, ResNet50, DenseNet) for accurate classification.

## Tasks
- **Data exploration**: one-hot encoding, class distribution analysis, and sample visualization.  
- **Baseline model**: Implement and evaluate a CNN with a fixed architecture.  
- **Model improvement**: Tune hyperparameters (≥ 6 variations), refine architecture (layers/filters), and compare performance.  
- **Transfer learning**: Utilize VGG16, ResNet50, or DenseNet121 for feature extraction and classification.  
- **Evaluation**: Report accuracy, precision, recall, F1 score, ROC curves, AUC scores, and confusion matrices.  
- **Discussion**: Cover literature-based enhancements and assess ethical implications (bias, privacy, security, societal impact).

## Technologies
- Python  
- TensorFlow / Keras  
- Matplotlib, NumPy, scikit-learn  
