# Imbalanced learning of Motor Vehicle Collisions on Public Roads in Canada

![Collision Image](image/photo.jpg)

In real-world datasets, class imbalance is a common problem. An imbalanced dataset occurs when one class (called the majority, or negative class) vastly outnumbered the other (called the minority, or positive class). The class imbalance problem is manifested when the positive class is the class of interest. We have obtained a real-world datasets in transportation collisions with an inherent imbalanced class problem.


##  Data set information:   [National Collision Database](https://open.canada.ca/data/en/dataset/1eb9eba7-71d1-4b30-9fb1-30cbdab7e63a)

##  Attribute Description:

- **C_YEAR**: Year

- **C_MNTH**: Month

- **C_WDAY**: Day of week

- **C_HOUR**: Collision hour

- **C_SEV**: Collision severity (this is the class attribute we are going to predict)

- **C_VEHS**: Number of vehicles involved in collision

- **C_CONF**: Collision configuration

- **C_RCFG**: Road way configuration

- **C_WTHR**: Weather condition

- **C_RSUR**: Surface condition

- **C_RALN**: Road alignment

- **C_TRAF**: Traffic control

- **V_ID**: Vehicle sequence number

- **V_TYPE**: Vehicle type

- **V_YEAR**: Vehicle model year

- **P_ID**: Person sequence number

- **P_SEX**: Person sex

- **P_AGE**: Person age

- **P_PSN**: Person position

- **P_ISEV**: Medical treatment required

- **P_SAFE**: Safety device used

- **P_USER**: Road user class


##  Project objectives

- Understand the causes of fatal accidents on public road in Canada. For example, the vehicle model, age group,  road conditions, etc.

- Build a machine learning model that would predict the type of motor vehicle collision: fatal or non-fatal.


##  Practice skills

In this project, we will learn the following  skills

- Data cleaning

- Exploratory Data Analysis

- Imbalanced learning & Cost sensitive method

- Under Sampling

- Synthetic Minority Over Sampling Technique (SMOTE)

-  Advanced classification models such as random forest classifier and XGBoost

- Precision Recall  (PR) Curve and Area Under the PR Curve (AUPR)

- Receiver Operating Characteristics (ROC) curve and Area Under the ROC (AUROC)