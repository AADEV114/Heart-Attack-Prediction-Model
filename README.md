*Disease Prediction Using Patient Medical Records*
-In this project, I've developed a classification-based machine learning model that predicts the presence of a disease in a patient based on various medical features. The dataset includes physiological and biochemical attributes such as age, gender, blood pressure, heart rate, blood sugar, and specific cardiac markers like CK-MB and Troponin levels.
-The target variable, labeled Result, indicates whether the patient is diagnosed as positive (diseased) or negative (healthy). This binary classification problem is addressed using a Random Forest Classifier, which is known for its robustness and interpretability.

Step-by-step working:-
--Data Preprocessing:
Handled missing values
Encoded categorical target labels (positive → 1, negative → 0)
Scaled numerical features using StandardScaler

--Model Building:
Data split into training and test sets (80/20)
Trained using Random Forest Classifier

--Evaluation:
Used accuracy, precision, recall, F1-score for performance
Visualized confusion matrix to observe model predictions
Analyzed feature importance to understand contributing medical parameters

Final Insights:
The model successfully identifies key indicators of the disease.
Features such as Troponin levels and CK-MB are typically significant in diagnosing cardiac conditions.
The confusion matrix highlights how well the model balances false positives and false negatives—critical in medical diagnostics.

--This model can serve as a basic decision-support tool in medical diagnostics, offering early insights based on patient vitals. It is an example of how data analytics can augment clinical expertise and improve early detection and resource allocation.

