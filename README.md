# automatic-anaerobic-threshold-detection
Automatic identification of the anaerobic threshold (AnT) from heart rate time series data using rule-based and machine learning (ML) Epoch-by-Epoch Recurrence Quantification Analysis (RQE).

Contains three notebooks:
1. Rule-Based RQE Exploration - exploration and development of baseline methodology of rule-based RQE pipeline, including Bayesian optimisation of the search window.
2. Rule-Based RQE - Application of pipeline developed in Rule-Based RQE Exploration to an unseen dataset.
3. ML RQE - Enhancement of the rule-based RQE pipeline with the integration of a candidate classifier stage to improve performance in general and when dealing with systematic outliers, e.g. early AnTs. 
