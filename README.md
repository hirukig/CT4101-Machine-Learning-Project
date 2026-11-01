# CT4101-Machine-Learning-Project
Detecting Phishing Websites  

Can machine learning be used to classify whether a URL is phishing or
legitimate using its extracted features?

Dataset: UCI Machine Learning Repository – PhiUSIIL Phishing URL (Website)
(https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)
Licence: This dataset is licensed under a Creative Commons Attribution 4.0
International (CC BY 4.0) license. This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.
Citation: Prasad, A. & Chandra, S. (2024). PhiUSIIL Phishing URL (Website) [Dataset].
UCI Machine Learning Repository. https://doi.org/10.1016/j.cose.2023.103545.

Target Variable: label (shows whether website is legitimate or phishing)
Main Features: URLSimilarityIndex, IsDomainIP, URLLength, DomainTitleMatchScore,
NoOfSubDomain, HasObfuscation, HasPasswordField
Number of Records: 235,795
Important Quality Issues: invalid values, duplicates of data, URLs from dataset may not
imitate the same threats we see today.

Baseline: Logistic Regression (target variable is binary)
Candidate Models: Decision Tree (main, will see non-linear patterns), SVM
Evaluation: Recall (don’t want to call a phishing website legitimate)
