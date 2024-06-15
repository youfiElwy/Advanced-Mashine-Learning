# Advanced Machine Learning Assignments

## Assignment 1: Ensemble Learning Models Comparison

### Objective
Explore and compare the performance of three popular ensemble learning models: Random Forest, AdaBoost, and Gradient Boost. Fine-tune these models on three distinct datasets, perform necessary preprocessing steps, and analyze the results to draw valuable insights.

### Tasks
- **Dataset Selection:** Choose three diverse datasets suitable for classification tasks.
- **Data Preprocessing:** Handle missing values, encode categorical variables, scale numerical features, and perform necessary data cleaning procedures.
- **Model Implementation:** Implement RandomForest, AdaBoost, and Gradient Boost models using Python with scikit-learn.
- **Hyperparameter Tuning:** Fine-tune hyperparameters using techniques like grid search or random search.
- **Training and Evaluation:** Train tuned models on datasets and evaluate performance using accuracy, precision, recall, F1-score.
- **Comparison Table:** Summarize accuracy for each model on each dataset.
- **Visualizations:** Create a bar chart comparing accuracy and a grid search heatmap for the best model per dataset.
- **Insights and Conclusions:** Report findings, strengths, weaknesses of each model, and performance on different datasets.

---

## Assignment 2: Video Classification using CNN-RNN Architecture

### Objective
Implement a CNN-RNN architecture for video classification using TensorFlow on the UCF101 action recognition dataset. Extract spatial features from frames using CNNs and model temporal relationships with RNNs for accurate action classification.

### Tasks
- **Dataset Handling:** Download UCF101 dataset, create dataframe with video paths and labels.
- **Data Preprocessing:** Extract and preprocess frames, optionally split dataset into training, validation, testing sets.
- **Feature Extraction with CNN:** Design CNN architecture (e.g., InceptionV3), extract spatial features from frames.
- **Sequence Modeling with RNN:** Implement RNN model (e.g., LSTM or GRU) to capture temporal dependencies.
- **Model Training:** Combine CNN-extracted features with RNN, compile model, train on training set with validation monitoring.
- **Evaluation:** Assess model performance on testing set using metrics like accuracy, precision, recall, F1-score, and visualize with confusion matrix.

---
