Customer Segmentation for Subscriptions
IDS 575 Machine Learning Statistics
02/26/2022
Project Idea
To attract more clients to pay a subscription, a dating application company aims to add new subscription tiers based on their age, income, and education. The sales staff has divided all of their consumers into four groups in their current market (A, B, C, D). 

Following that, they conducted segmented outreach and communication for several client segments. They've had a lot of success with this method. They intend to apply the same method to additional markets, and they have found 2627 new potential clients. 

Create a machine learning model to assist the application in predicting the proper type of incoming consumer.

Project Scope
Developing a model based on a clustering algorithm to predict customer segments based on various parameters. We will work on the historic data collected by the company to build and train a machine learning model. 
Also, we will use various techniques to evaluate the model accuracy. This clustering prediction model with suitable datasets and data features can be used to predict segments in use-cases like the targeted audience.

Machine Learning Workflow
To develop a prediction model, we will go through the following stages:
•	Analyze and explore acquired data
•	Develop prediction model
•	Train developed model
•	Evaluate model accuracy
•	Tune hyperparameters
•	Deploy your trained model
•	Visualize prediction requests to your model

Exploratory Data Analysis of the dataset
Our data shape contains 10695 rows and 11 columns. The 11 variables in our dataset are: ID, Gender, Ever_Married, Age, Graduated, Profession, Work_Experience, Spending_Score, Family_Size, Var_1, and Segmentations. 7 Variable categorical and 4 are numerical. We do have missing values in 6 different features. The number of rows decreased to 8819 after we dropped the missing values. 
•	Some of the variable names were changed: Ever_Married -> Marital _Status, Var_1 -> Income_Cat
•	The Gender Distribution reveals 44.9% (3958) of the population are male and 55.1% (4861) are female. 
•	There are 9 unique categories in the profession attribute, where the most popular professions are Artist, Healthcare, and Entertainment. 
•	More than 5000 customers indicated that they have graduated from college, while 3000 claimed that they ha¬ve not. Similar trend was displayed on the Ever_Married variable as well.
•	Lastly, a heatmap discloses that Age, Graduated, Work_Experience, and Speding_Score have the highest correlation to segmentation classes. 

Implementation Timeline/Schedule

Phases	Tentative Dates	Goals
Project Commencement & Planning	Feb 20, 2022	We will be brainstorming ideas individually and then discuss our inputs with the group to finalize on a topic. 

We will explore the data to decide upon the features and variables that we will be using going forward.
Midterm Report	Feb 28, 2022	We will be cleaning the data, removing null values and outliers and will be further performing exploratory data analysis. 
Performance/
Monitoring	Mar 14, 2022	We will build models for predictions and monitor their performances.

We will then be running various procedures for each model and then evaluate which model gives the best accuracy.
Final submission	Apr 17, 2022	We will be summarizing our discoveries and model performances by doing visualization.

Then we will do Model comparison to Initial segmentation.

Expected Outcome
We expect the models to be able to group similar data points together and discover their pattern. Based on the patterns, we will be able to classify customers into different segments according to their characteristics. We also expected the models to give us an accuracy of at least 65% since the heatmap shows that ‘Age’, ‘Graduated’, and ‘Spending_Score’ are the major contributors to segmentation. 

Future Scope
We’ll try to implement DBScan clustering (unsupervised learning method) and then compare the outcomes with K-Means prediction and analyze which model gives best result. We’ll do the visualizations based on outcomes, while comparing model with its initial segmentation

