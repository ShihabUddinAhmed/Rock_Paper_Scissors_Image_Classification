This project implements an end-to-end image classification system for recognizing rock, paper, and scissors hand gestures using PyTorch. It includes data preprocessing, model training, evaluation, error analysis, and deployment using webcam-captured images.

Two approaches were explored: a custom Convolutional Neural Network (ConvNet) built from scratch, and a pre-trained MobileNet model using transfer learning. The models were compared based on performance, generalization, and overfitting behavior.

The project also extends to real-world deployment by collecting a new dataset using a webcam, fine-tuning the best-performing model, and analyzing performance differences between the original and new data distributions.

Key features:
	•	Stratified dataset splitting (train/dev/test)
	•	Custom CNN architecture with Conv2D, ReLU, and MaxPooling
	•	Transfer learning using MobileNet
	•	Early stopping and fine-tuning techniques
	•	Confusion matrix and error analysis
	•	Webcam data collection and evaluation

This project demonstrates practical machine learning workflow, including model generalization challenges and domain adaptation.
