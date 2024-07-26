# Facial Emotion Recognition Using Convolutional Neural Network-Based Classification

# Overview
This project aims to develop a facial emotion recognition system using Convolutional Neural Networks (CNN). The system classifies facial emotions into various categories by leveraging deep learning techniques.

# Key Activities
Data Pre-processing
• Data augmentation to increase the diversity of the training data.
• Rescaling pixel values to normalize the input data.
• Applying random rotations and shifts to make the model more robust.

# Model Training
• Implementing the CNN model.
• Performing stratified K-fold cross-validation with different splits: 90:10, 80:20, 70:30, 60:40, 50:50.
• Splitting the data into training and testing sets.

# Evaluation
• Calculating performance metrics such as accuracy, precision, recall, and F1-score.
• Plotting and printing the confusion matrix to visualize the model's performance.

# Result and Discussion
• Analyzing the performance metrics obtained from the K-fold cross-validation.
• Comparing the performance metrics of each data split and emotion class.
• Identifying patterns and insights from the results.

# Repository Structure
• data/ - Contains datasets used in the study.
• notebooks/ - Jupyter notebooks with data preprocessing, integration, and model training steps.
• models/ - Saved models for CNN.
• results/ - Performance metrics and comparison results.
• scripts/ - Python scripts for data preprocessing, model training, and evaluation.
• README.md - Project overview and details (this file).

# Usage
• Data Pre-processing
Execute the data_preprocessing.ipynb notebook to clean and prepare the data.
• Model Training
Train the CNN model using train_cnn.py.
• Evaluation
Evaluate model performance using evaluate_models.ipynb.

# Results
The results of the analysis will be saved in the results/ directory. Detailed discussions and insights are provided in the results_and_discussion.ipynb notebook.

# Acknowledgements
This project was completed as part of the final year project at Universiti Teknologi Malaysia. Special thanks to all who provided guidance and support throughout the project, especially my supervisor: Prof. Madya Ts. Dr. Rohayanti Binti Hassan; My examiners: Dr. Haslina Binti Hashim and Dr. Nies Hui Wen; and my academic advisor: Dr. Noor Hidayah Binti Zakaria.
