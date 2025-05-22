# 🧴 Dermatology Disease Classification
This project performs machine learning-based classification of dermatological diseases using clinical features from a dermatology dataset. The goal is to preprocess data, evaluate multiple ML algorithms, and determine the best-performing model using metrics like accuracy, classification report, and cross-validation.

📁 Dataset
Source: dermatology_database_1.csv
Features: 33 clinical attributes (symptoms)
Target: Disease class (6 categories)
Missing values in the age column are handled and imputed using the median before standardizing the data.

📊 Models Used
The following classification models were implemented and compared:
1. Logistic Regression
2. Random Forest
3. Support Vector Machine (RBF Kernel)
4. K-Nearest Neighbors (KNN)

Each model is trained, tested, and evaluated using:
1. Accuracy Score
2. Classification Report (Precision, Recall, F1-Score)
3. Confusion Matrix
4. 5-Fold Cross-Validation (for Random Forest)

🔄 Workflow Summary
1. Data Preprocessing
-Replace ? with NaN and convert age to numeric.
-Impute missing values.
-Standardize all features.
2. Model Training & Evaluation
-Train on 80% of data, test on 20% (stratified).
-Evaluate all four models.
3. Visualization
-Display confusion matrix heatmaps for each model.
4. Cross-Validation
-Perform 5-fold CV on the Random Forest model.
