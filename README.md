# Predicting-Credit-Card-Customer-Segmentation
A machine learning assignment in which I had to focus on researching and analyzing available related solutions to the problem and recommend an improvement or an entirely new solution.
## Things I learned/revised:
* Data Cleaning
  * No null and duplicated values were present.
  * Potential outlier can be seen from positively skewed numerical data based on the plotted histogram and boxplot.
* Data Analysis (EDA)
  * Male and Female data is fairly distributed based on pie chart.
  * Despite the data imbalance in categorical variables, no significant categorical variable shows a strong indicator for attrition occurence (target variable).
* Feature Encoding
  * One hot encoding to convert input features into numerical data for training and processing of ML algorithms.
* Hyperparameter Tuning
  * Optuna Bayesian Optimization is used to optimized ADABOOST and XGBOOST algorithm.
  * Optuna optimization improved AdaBoost performance, making it a better model than the result of related works.
* Model Evaluation through evaluation metrics such as Accuracy, Precision, Recall, F1 score and AUCROC score.
  * The number of false negatives (want to capture as many actual churn cases as possible) which is what is focused on to minimized are the same for both models and that is 2% of the total data.
  * Due to imbalance data, F1 score and AUCROC score is heavily taken into consideration. XGBOOST had slightly better score than ADA in terms of both metrics.
  * Recall score were the same for both algorithm but XGB performed slightly better than ADA in other metrics.
## Afterthoughts on the assignment:
The assignment served as a good experimentation project in which I get to try on new solutions such as using Optuna Bayesian Optimization and helped me improve my analytical thinking in which I had to analyze existing solutions
and try to implement new improved solutions on the existing problem.
### The documentation of the project is <a href="https://sdtaylorsedu-my.sharepoint.com/:b:/g/personal/limjiajie06_sd_taylors_edu_my/EbVRWHsh6opIpf16cZq1rGEBAwd2H7ECBzeEchCedlfmog?e=g6Mvd9" rel="nofollow">here</a>
