# Day 8 Tasks

## 1. Try different algorithms on the same dataset
**What this means:** Instead of focusing on one model only, we will compare several algorithms and see which one performs best on your dataset.
**What to do:**
- Use your training and testing data from Day 6.
- Train at least 4 different algorithms such as:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - SVM
  - KNN
  - Naive Bayes
- For each model, print the training score and test score.
- For classifiers, use accuracy or F1-weighted. For regressors, use RMSE.

## 2. Check whether the model is underfitting, overfitting, or just right
**What this means:** A model can be too simple, too complex, or balanced.
**What to do:**
- Compare the training score and test score for each algorithm.
- Decide whether each result is:
  - **Underfitting**: both scores are low
  - **Overfitting**: training score is very high, but test score is much lower
  - **Just right**: both scores are good and fairly close
- Write a short note for each model explaining your observation.

## 3. Use cross-validation to verify the results
**What this means:** A single test score may not be enough, so we should check whether the model is consistent.
**What to do:**
- Use `cross_val_score(model, X_train, y_train, cv=5)` for each algorithm.
- Print the mean score and standard deviation.
- Identify which algorithm seems the most reliable.

## 4. Compare the models and write a conclusion
**What this means:** We want to understand which algorithm works best for your dataset.
**What to do:**
- Create a small comparison table with the model name, training score, test score, and cross-validation score.
- Decide which model is the best overall.
- Write 3–5 lines explaining why that model performed better and whether it was underfitting, overfitting, or just right.

*Colab Link:* https://colab.research.google.com/drive/1rC5UxK1aNfNNWomAH5vQcu_Qszuzv6Gl?usp=sharing