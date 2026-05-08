**Project Overview**
The Titanic Survival Prediction project is a classic beginner machine learning project that uses real passenger data from the 1912 Titanic disaster to predict whether a passenger survived or not. It is widely used as a first step into the world of data science and machine learning.
Using features like passenger age, gender, ticket class, and fare, we train a machine learning model to classify passengers as 'Survived' or 'Did Not Survive'.

**Project Objectives**
•	Understand and explore a real-world dataset
•	Clean and preprocess data (handle missing values, encode categories)
•	Perform Exploratory Data Analysis (EDA) with visualizations
•	Train a machine learning classification model
•	Evaluate model performance using accuracy metrics
•	Gain hands-on experience with Python data science libraries


**Project Steps**
Step 1 — Load & Explore Data
Load the CSV dataset using Pandas and explore its structure, data types, and basic statistics. Identify missing values and understand the distribution of key features.
Step 2 — Data Cleaning
Handle missing values in columns like Age and Embarked. Drop irrelevant columns such as Name, Ticket, and Cabin. Convert categorical variables (like Sex) into numerical values using encoding.
Step 3 — Exploratory Data Analysis (EDA)
Create visualizations to uncover patterns in the data. Key insights explored include survival rates by gender, ticket class, and age group using Seaborn and Matplotlib.
Step 4 — Model Training
Split the data into training (80%) and testing (20%) sets. Train a Random Forest Classifier on the training data and allow it to learn survival patterns from the features.
Step 5 — Model Evaluation
Evaluate the trained model on the test set using accuracy score. The model typically achieves 80–85% accuracy on unseen data.


**Key Findings**
•	Women had a significantly higher survival rate than men (approx. 74% vs 19%)
•	1st class passengers survived more than 2nd and 3rd class passengers
•	Children (age < 10) had a higher chance of survival
•	Passengers who paid higher fares had better survival odds
•	The famous 'women and children first' rule is clearly visible in the data
