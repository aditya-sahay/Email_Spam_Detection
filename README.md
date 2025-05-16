# Email Spam Detection using Logistic Regression

## Project Overview
This project implements an Email Spam Detection system using Logistic Regression. The goal is to classify emails as spam or non-spam based on their textual content. Logistic Regression is used due to its efficiency and effectiveness in binary classification problems.

## Dataset
The dataset used is given above.

## Project Steps

1. **Data Collection**  
   Collected emails from the dataset.

2. **Text Preprocessing**  
   - Converted all text to lowercase  
   - Removed stopwords and punctuation  
   - Cleaned and normalized the email text  

3. **Feature Extraction**  
   Used `CountVectorizer` to transform the text data into numerical features suitable for model training.

4. **Model Building**  
   Built a Logistic Regression model using `LogisticRegression()` from scikit-learn.

5. **Train/Test Split**  
   Split the dataset into training and testing sets to evaluate model performance on unseen data.

6. **Model Training**  
   Trained the model on the training dataset.

7. **Evaluation**  
   Evaluated the model using accuracy, precision, recall, and the confusion matrix.

## How to Run
1. Clone the repository  
2. Install dependencies (e.g., scikit-learn, pandas, nltk)  
3. Run the preprocessing and training scripts  
4. Evaluate the model performance

## Metrics
- Accuracy: Measures overall correctness  
- Precision: Measures spam prediction quality  
- Recall: Measures spam detection rate  
- Confusion Matrix: Visualizes true/false positives and negatives

## Future Improvements
- Try other models like SVM or Random Forest  
- Use more advanced NLP techniques  
- Perform hyperparameter tuning  

---

**Author:** Aditya Sahay 
**Date** 2025
