# BioinformaticsProject

1) Data Preprocessing: The project started with data preprocessing, where the input dataset (GSE103334_FPKM_CKP25_TOPHAT.txt) was read using pandas. The dataset was then transformed and prepared for further analysis.

2) Feature Selection: Four feature selection techniques were applied to the dataset, namely Variance Threshold, SelectKBest, Feature Importance, and Principal Component Analysis (PCA). These techniques were used to identify the most relevant features for the classification task.

3) Ensemble Classification Techniques: Four ensemble classification techniques were implemented and compared: Random Forest, XGBoost, CatBoost, and Bootstrap Accumulation (Bagging). These algorithms were chosen for their effectiveness in handling complex classification problems.

4) Model Evaluation: The performance of each ensemble technique was evaluated using various metrics, including accuracy, precision, recall, and F1-score. Cross-validation was performed to assess the generalization capability of the models.

5) Results and Visualization: The results were visualized using box plots to compare the performance of the ensemble techniques. The box plots provided insights into the variation in performance across different metrics and algorithms.
