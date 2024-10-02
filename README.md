The ensemble model is built using a combination of the best 4 performing 
models. The models evaluated consist of Decision Tree Classifier, Random Forest 
Classifier, AdaBoost Classifier, KNeighborsClassifier, SGD Classifier, ExtraTrees 
Classifier, GaussianNB, and XGBClassifier. This ensemble approach employs a 
Voting Classifier with hard voting, which combines multiple base models to enhance 
predictive performance. The integration of various models aims to capture a broader 
range of patterns and features associated with malicious URLs, thereby improving the 
detection system's overall performance. 

The final proposed model involves the collection of a Kaggle dataset containing benign and 
malicious URLs. Features are then extracted from these URLs to create both balanced and 
imbalanced datasets. The data is then split into training (80%) and testing (20%) sets. 
Various classifiers, including Decision Tree, Random Forest, AdaBoost, KNeighbors, 
SGD, ExtraTrees, GaussianNB, and XGB, are trained on the dataset. The top four 
performing models are selected for an ensemble voting classifier using hard voting to 
enhance prediction accuracy. This classifier is evaluated using cross-validation, 
specifically StratifiedKFold with 5 folds, to ensure reliability and robustness before 
making final predictions. The process flow, illustrated in the accompanying flowchart, 
emphasizes the use of ensemble learning, hard voting, and data balancing techniques 
to improve the classification of malicious URLs.

![image](https://github.com/user-attachments/assets/9d6d8403-92aa-4ff5-bdf8-2b8981d50e0d)


Project by: Nur Irdina Binti Hassan

Multimedia University, Cyberjaya
