# Fruit Classification using CNN

## Overview
This project predicts the type of fruit from an image using the [Fruits-360 dataset](https://www.kaggle.com/datasets/moltean/fruits).  
The workflow involves image preprocessing, convolutional neural network (CNN) model design, training, evaluation, and comparison of multiple architectures.

## Project Workflow
1. **Data Exploration**  
   - Grouped and analyzed images by fruit category.  
   - Visualized sample images for inspection.  
   - Performed clustering analysis for exploratory insights.

2. **Model Design and Training**  
   - Implemented CNN models with `classification_report` to evaluate performance.  
   - Designed and trained three CNN architectures for comparison.

3. **Model Tuning**  
   - Applied hyperparameter tuning where necessary to improve accuracy.  

4. **Model Evaluation**  
   - Used a separate test set to assess generalization performance.  
   - Evaluated precision, recall, F1-score, and accuracy.  
   - **Model 1:** 94% accuracy, strong performance but slight overfitting signs after epoch 2.  
   - **Model 2:** 68% accuracy, significant overfitting, poor generalization.  
   - **Model 3:** Strong overall performance (accuracy close to Model 1) with better generalization.

5. **Architecture Comparison**  
   - Compared results of all three CNNs.  
   - Identified overfitting patterns and recommended architecture adjustments for improvement.

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  

## Dataset
Fruits-360 dataset from Kaggle:  
[https://www.kaggle.com/datasets/moltean/fruits](https://www.kaggle.com/datasets/moltean/fruits)
