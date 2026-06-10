# Credit Scoring Model

## Objective
Predict whether a customer is creditworthy using machine learning.

## Dataset
German Credit Dataset

## Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Libraries
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
## Results

Three machine learning algorithms were trained and evaluated for credit risk prediction.

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---------|---------|---------|---------|---------|---------|
| Logistic Regression | 66.5% | 71.60% | 86.43% | 78.32% | 66.56% |
| Decision Tree | 73.0% | 77.22% | 87.14% | 81.88% | 72.10% |
| Random Forest | 77.0% | 79.38% | 90.71% | 84.67% | 77.83% |

### Key Findings

- Logistic Regression achieved satisfactory performance with 66.5% accuracy.
- Decision Tree improved the prediction accuracy to 73.0%.
- Random Forest outperformed all other models with 77.0% accuracy and 77.83% ROC-AUC score.
- Random Forest achieved the highest Recall (90.71%), making it effective for identifying creditworthy customers.
- Based on the evaluation metrics, Random Forest was selected as the best-performing model for credit scoring.

### Conclusion

This project successfully developed a Credit Scoring Model using Machine Learning techniques to predict customer creditworthiness. Multiple classification algorithms were implemented and compared, including Logistic Regression, Decision Tree, and Random Forest. Among them, Random Forest achieved the best overall performance with 77.0% accuracy, 79.38% precision, 90.71% recall, and 84.67% F1-score. The model can assist financial institutions in making data-driven credit approval decisions and reducing lending risk.

## Author
chandaluri Lakshsmi Swapna
CodeAlpha Machine Learning Internship
