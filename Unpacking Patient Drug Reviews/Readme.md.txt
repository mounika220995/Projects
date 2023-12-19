Introduction

In this comprehensive analysis, we delved into the Drug Review Dataset sourced from the UCI Machine Learning Repository, comprising 215063 entries with seven distinct features. Our primary objective is to predict the condition based on user reviews. This report outlines our roadmap, beginning with data exploration and preprocessing, followed by feature engineering, to ultimately develop a robust model capable of predicting conditions from user reviews. Through this endeavor, we aim to provide valuable insights into the factors influencing user satisfaction in the realm of pharmaceutical reviews.

Methodology

Exploratory Data Analysis
Exploratory data analysis (EDA) is performed to gain a comprehensive understanding of the dataset. Through this analysis, we successfully pinpointed the top 10 prevalent medical conditions, explored the distribution of ratings, and delved into the daily review trends over time.

Data Preprocessing
The data preprocessing phase prioritized data integrity by eliminating null values and enhancing textual data quality through the removal of special characters, stop words, and repeating patterns. Further refinement included filtering for the top 10 conditions with over 4000 reviews, and the application of label encoding to categorical variables, paving the way for a more structured and informative dataset.

Predictive Modeling
In our predictive modeling endeavors, we applied logistic regression, random forest, and XGBoost algorithms to forecast user condition based on reviews. Impressively, our models achieved notable accuracies, with logistic regression reaching 88.1%, random forest demonstrating strong performance at 92.6%, and XGBoost yielding an accuracy of 89.5%. These results underscore the efficacy of our predictive frameworks.

Topic Modelling 
In our exploration of user reviews related to the top 10 medical conditions, we utilized SpaCy and Gensim libraries to implement an LDA model. This facilitated the extraction of five dominant topics, shedding light on nuanced themes within the dataset. The resulting structured topics offer valuable insights into prevalent aspects of patient/user experiences, enhancing the interpretability of the drug review corpus.


Key Takeaways

•	Sentiment Analysis – Observed high frequency of neutral reviews.
•	Identified five dominant topics using successful topic modeling techniques.
•	Evaluated Logistic Regression, Random Forest, and XGBoost models for predicting user 	conditions based on user reviews.
•	Network analysis of condition – drug relationships.



Future Scope

•	Explore Deep learning, ensemble methods to further optimize the predictive model.
•	Real-Time drug suggestions via Virtual Medical Assistant.
•	Real-Time integration of reviews for continuous monitoring to improve the quality of the 	content of reviews.




Dataset we used

“Kaggle UCI ML Drug Review dataset”                        https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018


References
We leveraged insights from a variety of Kaggle notebooks as valuable references throughout the progression of our project.

































