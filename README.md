🧠 Task 4: Classification using Logistic Regression

📌 Objective
- Build a binary classifier using logistic regression on the Breast Cancer Wisconsin dataset

🛠️ Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

📁 Dataset
- Dataset used: Breast Cancer Wisconsin

✅ Steps Performed
1. Loaded and inspected the dataset
2. Encoded target labels (Malignant = 1, Benign = 0)
3. Dropped unnecessary columns
4. Standardized features
5. Performed train-test split
6. Trained a logistic regression model
7. Evaluated model using accuracy, precision, recall, F1-score, ROC-AUC
8. Plotted confusion matrix and ROC curve
9. Tuned threshold and visualized precision-recall trade-off

📊 Key Evaluation Metrics
| Metric     | Score     |
|------------|-----------|
| Accuracy   | 0.97      |
| Precision  | 0.96      |
| Recall     | 0.98      |
| F1-Score   | 0.97      |
| ROC-AUC    | 0.97      |

📈 Visuals
- Confusion Matrix
- ROC Curve
- Precision vs Recall Curve

🧠 Sigmoid Function
Logistic regression uses the sigmoid function to convert input into a probability:
[sigma(z) = \frac{1}{1 + e^{-z}}]

- If the predicted probability > 0.5, the model classifies it as class 1
- The threshold can be adjusted to optimize for different evaluation metrics

📎 Files
| File                | Description                             |
|---------------------|-----------------------------------------|
| Task 4.ipynb        | Code for logistic regression pipeline   |
| data.csv            | Input dataset                           |
| README.md           | This file with project explanation      |

💡 What I Learned
- Binary classification and sigmoid curve
- Model evaluation: accuracy, recall, precision, F1, ROC-AUC
- How to interpret model coefficients
- Threshold tuning using precision-recall analysis
