# Introduction:
The project, titled "Auditing for Bias," addresses the assessment of potential bias in a machine learning model trained on the ProPublica COMPAS dataset, specifically focusing on predicting recidivism in criminal cases. The aim is to determine if bias exists towards African-American or Caucasian defendants in terms of false positive rates and calibration, while also exploring the societal implications of using such an algorithm in the criminal justice system.

# Tech Stack:
- Programming Language: Python
- Libraries: pandas, scikit-learn
- Models: Logistic Regression, Random Forest, AdaBoost
- Data Visualization: Matplotlib, Seaborn

# Features:
1. **Dataset Preparation:** Splitting the ProPublica COMPAS dataset into training and test sets.
2. **Pre-Processing:** Transforming categorical variables into numerical format, handling null values, and creating new columns for race binary values.
3. **Exploratory Data Analysis:** Visualizing the distribution of decile scores for African-American and Caucasian individuals.
4. **Logistic Regression:** Training a logistic regression model, evaluating accuracy, and analyzing the confusion matrix.
5. **Feature Importance:** Identifying key features impacting the model's output.
6. **Random Forest:** Implementing a decision tree and random forest classifier, assessing accuracy and confusion matrix.
7. **AdaBoost:** Employing AdaBoost with 50 weak learners, evaluating accuracy, and analyzing the confusion matrix.
8. **Model Evaluation:** Comparing model performances with and without considering race variables.

# Process:
The project began with data preparation and pre-processing, ensuring a clean and numerical dataset for machine learning. The team experimented with logistic regression, random forest, and AdaBoost models, assessing their accuracy and bias. Visualizations helped understand the impact of race on decile scores. Challenges included handling biases and interpreting model outputs. Conclusions were drawn based on the models' performance, emphasizing the need for fairness in predictive algorithms.

# Learnings:
1. Understanding the importance of fair and unbiased machine learning models in sensitive domains like criminal justice.
2. Hands-on experience with logistic regression, random forest, and AdaBoost algorithms.
3. Interpretation of confusion matrices and feature importance scores.
4. Realizing the significance of ethical considerations in data science projects.

# Improvements:
1. Incorporating more advanced fairness metrics to comprehensively evaluate model bias.
2. Exploring alternative models or techniques specifically designed for fairness in predictions.
3. Conducting a deeper analysis of the societal implications of biased predictions in the criminal justice system.
4. Considering additional demographic variables beyond race for a more comprehensive assessment of bias.
5. Continuous monitoring and re-evaluation of the model's fairness as new data becomes available.
