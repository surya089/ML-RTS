**Machine Learning project-RTS (Road Traffic Accidents Severity) Prediction app url is  https://rta-app-t1ce.onrender.com**


**Project: Road Traffic Severity Classification**

**Description:** This data set is collected from Addis Ababa Sub-city police departments for master's research work. The data set has been prepared from manual records of road traffic accidents of the year 2017-20. All the sensitive information has been excluded during data encoding and finally it has 32 features and 12316 instances of the accident. Then it is preprocessed and for identification of major causes of the accident by analyzing it using different machine learning classification algorithms.

**Problem Statement:** The target feature is **Accident_severity** which is a multi-class variable. The task is to classify this variable based on the other 31 features step-by-step by going through each day's task. Your metric for evaluation will be **f1-score**

->Data contains 12316 samples and 32 features. There is 1 timestamp, 2 int and rest all categorical features. Target is categorical.

->This is a multi-class classification problem. Target is imbalanced and requires some form of resampling.

->Dropping columns that can cause imbalance while imputation 'vehicle_defect', 'vehicle_driver_relation', 'casualty_work', 'casualty_fitness'

**Encoding:** ordinal encoding, 
**Sampling:** Upsampling using smote, 
**Model:** RandomForestClassifier, 

