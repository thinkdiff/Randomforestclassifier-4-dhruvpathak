📂 Dataset:

Source: Kaggle Breast Cancer Dataset

Features: Includes 30 numerical features extracted from breast mass images.

Target: diagnosis — Malignant (M = 1) or Benign (B = 0)

⚙️ Workflow:

Data Cleaning:

Removed irrelevant columns (id)

Converted categorical target labels into binary numeric format

Feature Scaling:

Applied StandardScaler to normalize the dataset

Data Splitting:

Train-test split using 80/20 ratio

Modeling:

Used RandomForestClassifier from scikit-learn

100 trees (n_estimators=100), random_state=42

Evaluation:

Achieved accuracy > 90%

Printed classification report and confusion matrix