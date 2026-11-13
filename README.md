# aipi510-week12-ml-pipeline

Question: Predict iris flower species from four flower measurements.
Dataset: scikit-learn built-in Iris dataset, 150 samples.
Method: Train/test split (80/20, stratified); StandardScaler + LogisticRegression.
Results: 93.3% test accuracy
Limitations: Small example dataset; an estimate on 30 test samples is not strong evidence of production performance.
Experiment to try: Change test_size=0.20 to 0.30, rerun all cells, and compare accuracy.
