This project was to determine student dropout using Behavioural and Psycological Data based on the OCEAN 5 model 
we have selected certain attributes which would hwlp us determine the student dropout based on the above.

Here’s a complete summary of your student dropout prediction project :

---

Student Dropout Prediction Using KNN and SVM

Project Summary:
Developed a predictive analytics model to accurately forecast student dropouts by leveraging machine learning techniques on a comprehensive dataset of 800 student records.

Objective:
To identify at-risk students and mitigate dropout rates by predicting dropout likelihood based on various behavioral and socio-economic factors.

Data Collection:
- Utilized a dataset comprising 3,007 records of student characteristics, including Multitasking, ExtraActivities, Synergy, Hardship, FinancialConstraint, Stability, Engagement, Wellness, Resilience, and Cooperation.

Methodology:
- Feature Engineering: Selected 10 relevant features to train models on key student attributes affecting dropout rates.
- Data Preprocessing: Employed StandardScaler to normalize features and RandomOverSampler to balance class distributions.
- Model Training:
  - K-Nearest Neighbors (KNN): Implemented with 10 neighbors and distance-based weighting to enhance accuracy.
  - Support Vector Machine (SVM): Utilized One-vs-Rest strategy and linear kernel for effective multi-class classification.
- Cross-Validation:
  - KNN: Achieved a mean cross-validation score of 95.38%.
  - SVM: Achieved a mean cross-validation score of 96.00%.
- Evaluation Metrics:
  - Accuracy: KNN: 97.38%, SVM: 96.00% on new test data.
  - Confusion Matrix and Classification Report: Generated to assess model performance in detail.
  - ROC Curve:Plotted to evaluate the trade-off between sensitivity and specificity, ensuring optimal threshold selection.

Results:
- KNN: Achieved a high accuracy of 97.38% on the new test set, demonstrating superior predictive performance.
- SVM: Achieved an accuracy of 96.00%, corroborating the reliability of the classification approach.
- Model Comparison: KNN slightly outperformed SVM, validating the efficacy of distance-weighted neighbor-based classification.

Conclusion:
Successfully built and validated machine learning models that predict student dropout likelihood with high accuracy, providing valuable insights for educational institutions to proactively address student retention challenges.

Tools and Technologies:
- Python: For data manipulation and model training.
- Libraries: Pandas, Seaborn, Matplotlib, Scikit-learn, Imbalanced-learn.
- Techniques: Cross-validation, StandardScaler, RandomOverSampler, Confusion Matrix, Classification Report, ROC Curve.
