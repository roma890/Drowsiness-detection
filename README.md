# Drowsiness-detection
This project focuses on detecting driver drowsiness using a Convolutional Neural Network (CNN) to classify images as either "drowsy" or "non-drowsy."
The goal is to help identify early signs of drowsiness to prevent accidents caused by fatigued driving. 

Introduction: Fatigued driving is a major cause of road accidents. This project uses a machine learning approach to detect whether a driver is drowsy based on images of their face. The project employs a CNN model, which has been trained and evaluated on a dataset of labeled driver images. 

Dataset: The dataset contains two categories of images: Drowsy: Images where the driver's eyes are closed or showing signs of fatigue. Non-Drowsy: Images where the driver's eyes are open and alert. The images were resized to 224x224 pixels for uniformity and stored in respective folders for training. 

Model Architecture: The CNN architecture used for this project includes: Convolutional Layers with ReLU activation followed by Max Pooling Fully Connected Layers to map feature representations to the output classes ("drowsy" or "non-drowsy") Softmax Output to predict probabilities for the two classes 

Training: The dataset was split into 70% training, 15% validation, and 15% test sets. The CNN was trained for 10 epochs using the Adam optimizer and cross-entropy loss. Data augmentation techniques, such as shuffling and batching, were applied to improve the model. 

Evaluation: The model was evaluated based on: Accuracy: 89% test accuracy was achieved. Precision, Recall, and F1-Score: Used to assess the balance between the true positives, false positives, and false negatives. Confusion Matrix: Visualized to analyze misclassifications. ROC Curve: Generated to evaluate the true positive rate against the false positive rate. Results Test Accuracy: 89.18% Validation Accuracy: 88.96% Precision, Recall, and F1-Score were calculated for a comprehensive performance overview.
