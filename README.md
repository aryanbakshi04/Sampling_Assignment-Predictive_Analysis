# Sampling_Assignment-Predictive_Analysis
Data Loading and Preprocessing
The dataset is imported and loaded into a pandas DataFrame.
The target variable is separated from the features, as indicated in the Class column. The data gets split into what's called the features (X) and the target (y) for further exploration.
Data Balancing
Synthetic Minority Oversampling Technique (SMOTE) is applied to handle the class imbalance by oversampling the minority class to guarantee a balanced distribution.
Random undersampling is then performed on the majority class to obtain another balanced dataset.
Sampling Techniques
In order to investigate the effect of sampling methods on model performance, the following five sampling techniques are used:

Random Sampling: Samples of different sizes are selected randomly from the data set.
Stratified Sampling: Samples are selected while preserving the ratio of each class in the original dataset.
Three more sampling methods are tailored to suit the needs of the study, guaranteeing diversity in data sampling approaches.
Machine Learning Models
Five different machine learning models are trained on the sampled datasets:

Logistic Regression
Random Forest Classifier
Decision Tree Classifier
Naive Bayes Classifier
Support Vector Machine (SVM)
Compare and Contrast
Accuracy is used as the main metric to evaluate each model.
Results are systematically recorded in a table format for detailed comparison.
The generated table, saved as results.csv, facilitates an analysis of which sampling technique yields the highest accuracy for each machine learning model.
This structured approach guarantees a thorough investigation into the impact of sampling on model performance and insight into how effective various techniques are.
