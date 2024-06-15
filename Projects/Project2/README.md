# Assignment 2: Video Classification using CNN-RNN Architecture

## Project Overview
Video classification is a challenging task that requires understanding both the spatial details (individual frames) and temporal flow (sequence of frames) of videos. This project explores the use of a combined Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) architecture to classify actions within videos. The CNN extracts spatial features from frames, while the RNN models temporal relationships between these features to achieve more accurate video classification.

## Tasks
1. **Dataset**
   - Utilize the UCF101 action recognition dataset from TensorFlow Datasets. Download the dataset and create a dataframe with video paths and labels.

2. **Data Preprocessing**
   - Define a method to extract frames from videos and preprocess each frame (e.g., resizing).
   - Optionally, split the dataset into training, validation, and testing sets during data loading.

3. **Feature Extraction with CNN**
   - Design a CNN architecture (e.g., InceptionV3) to extract spatial features from each video frame.
   - Implement a feature extractor to process all frames per video and extract features.

4. **Sequence Modeling with RNN**
   - Implement an RNN sequence model (e.g., LSTM or GRU) to capture temporal relationships between the extracted frame features.

5. **Model Training**
   - Combine CNN-extracted features with RNN for sequence modeling.
   - Compile the model with an appropriate optimizer and loss function for multi-class classification.
   - Train the model on the training set, monitoring validation loss to prevent overfitting.

6. **Evaluation**
   - Evaluate the model's performance on the testing set using metrics like accuracy, precision, recall, and F1-score.
   - Compute and visualize a confusion matrix to analyze classification performance across different action classes.

---
