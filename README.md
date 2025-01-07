Predicting Driver Concentration Levels: A Machine Learning Approach to Enhancing Road Safety
Title
PREDICTING DRIVER CONCENTRATION LEVELS: A MACHINE LEARNING APPROACH TO ENHANCING ROAD SAFETY

Abstract
Urban roadways are often busy, posing challenges for drivers. This paper aims to determine the accuracy rate of drivers using concentration, response time, and stress management scores. Machine learning techniques are employed to evaluate and predict driver performance, enhancing road safety by identifying key factors affecting concentration and response times.

Keywords: Roadways, Concentration Score, Response Time Score, Stress Management, Machine Learning Techniques.

I. Introduction
Bus drivers are responsible for transporting passengers, navigating complex roadways, and ensuring safety. Maintaining concentration is vital for handling traffic, responding to unexpected situations, and managing stress. This study examines how factors like concentration, response time, and stress management affect driver performance. By analyzing these factors using machine learning, the goal is to improve driver safety and decision-making, reducing risks on the road.

1.1 Problem Description
The study focuses on predicting bus and van driver performance based on data from concentration, response time, and stress management scores. Various machine learning algorithms such as Random Forest, AdaBoost, and Gradient Boosting are tested to identify the most effective model for predicting performance. Evaluation metrics like the Kappa statistic are used to assess model accuracy and reliability.

1.2 Literature Survey
Anna Tzortzi et al.: Statistical analysis, including Shapiro-Wilk and Chi-square tests, was used to analyze driver data and identify key features affecting performance.
Tamilarasan Muniyapillai et al.: Face-to-face interviews were conducted, with Chi-square tests and binary logistic regression applied to study the factors influencing driver concentration.
Raymond Ghandour et al.: The research investigates the correlation between driver distractions and stress levels.
Tina Cvahte Ojstersek and Darja Toppolsek: The study focuses on detecting distractions and understanding traffic changes that influence driver behavior.
II. Methodology
2.1 Architecture
The collected data undergoes pre-processing to remove noise and handle missing values. It is then fed into various machine learning models for training and evaluation, after which accuracy is determined.

2.2 Algorithms
Decision Tree: Splits data into subsets, calculating accuracy through information gain and entropy.
K-Nearest Neighbor: Predicts outcomes based on the nearest neighbors in the dataset.
Logistic Regression: Analyzes the probability of outcomes based on input features.
Random Forest: Uses multiple decision trees to predict accuracy by averaging results.
AdaBoosting: Builds sequential models to correct errors in previous models, enhancing classification performance.
Gradient Boosting: Sequential models correct previous errors to improve classification accuracy.
XGB Classifiers: Utilizes decision trees and high-level training methods to reduce overfitting and improve accuracy.
Cohen’s Kappa: Measures the agreement between classifiers, especially in cases with categorical decisions.
III. Data Description
This section provides an overview of the dataset used in the project, including the features (concentration score, response time score, and stress management score) and their relevance to driver performance.

IV. Results and Discussion
The results are based on machine learning algorithms applied to the concentration, response time, and stress management scores. The best-performing models are chosen, with their respective accuracy values analyzed. Fine-tuning of the most accurate models is performed to achieve the highest accuracy.

V. Conclusion
This study demonstrates the effectiveness of machine learning models, particularly AdaBoost, in predicting driver concentration levels. The model's ability to handle both linear and non-linear relationships made it the most accurate. Future work could focus on incorporating additional features like weather conditions, traffic density, and behavioral data, as well as exploring deep learning models for more advanced insights.

