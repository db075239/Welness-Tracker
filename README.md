Wellness Tracker: Data-Driven Health & Fitness Insights
This project focuses on leveraging data analytics and machine learning to provide valuable insights into health and fitness data, ultimately aiming to enhance user engagement and commitment to their fitness journey. We developed a comprehensive system that includes in-depth data analysis, predictive modeling, user segmentation, and a personalized workout recommendation application.

Project Overview
Our primary goal was to extract actionable insights and patterns from a health and fitness dataset to empower users and benefit businesses in the wellness sector. We employed a combination of descriptive analytics (Data Analysis) and advanced data mining techniques (Classification, Clustering, Collaborative Filtering).

1. Data Analysis: Unveiling Fitness Benefits
In the initial phase, we conducted extensive data analysis to demonstrate the tangible benefits of fitness and how our proposed application can contribute to users' overall well-being. This involved exploring various aspects of health and lifestyle, such as:

Workout Trends: How activity types vary across different demographics (age, gender, BMI).

Activity Effectiveness: Identifying the most effective activity types based on calories burned.

Lifestyle Impact: Analyzing how factors like smoking affect health metrics (stress, sleep, exercise duration, intensity).

Demographic Influence: Understanding how demographic information impacts fitness performance (exercise duration, steps count, intensity).

Health Correlations: Investigating relationships between blood pressure and stress levels, BMI and physical fitness, and hydration levels with average heart rate during exercise.

Daily Steps Patterns: Examining the average number of steps per stress level and age group.

These insights highlight the crucial connections between activity, health indicators, and lifestyle choices, demonstrating why consistent engagement with a fitness tracking app is beneficial.

You can explore interactive dashboards and gain deeper insights into our data analysis findings here:
Tableau Public Dashboard

2. Data Mining: Predictive Insights & Personalization
The data mining phase involved building intelligent models to predict user behavior and offer personalized experiences:

User Churn Prediction (Classification)
Goal: To identify users who are at risk of discontinuing their fitness tracking or service subscriptions. This is crucial for businesses to intervene early and improve retention.
Methodology: We developed a robust user churn prediction system using a Random Forest Classifier. To address data imbalance (fewer users quitting than retaining), we applied SMOTE (Synthetic Minority Over-sampling Technique) on the training data. The model accurately classifies users as "Retained" or "At Risk of Quitting" based on their activity frequency, sleep quality, stress levels, and other health/activity data.
Benefit: Provides valuable insights for health and wellness centers and fitness apps to proactively engage with users and reduce churn.

User Segmentation (Clustering)
Goal: To identify distinct types of users based on their health and activity habits, enabling tailored recommendations and fostering connections among similar users.

Initial Approach (Workout Intensity): We first attempted to cluster users based on their average workout intensity and activity types. While this provided some grouping, the clusters were not as distinct as desired.

Refined Approach (Health & Fitness Metrics): We then performed a more comprehensive segmentation, clustering users into four distinct behavioral groups based on a wider range of demographic and fitness habits (e.g., age, BMI, duration, calories burned, sleep, stress, steps, hydration, fitness level). These clusters include:

Young, High-Activity Users: Active individuals benefiting from performance-focused programs.

Older, Consistent Exercisers: Users maintaining steady workouts, ideal for endurance plans.

Older, Low-Activity Group: Participants with short, low-intensity sessions, suited for beginner routines.

Young, Inefficient Exercisers: Younger users with high heart rates but low output, needing structured training and stress management.

Benefit: This refined clustering allows for highly targeted advertising, personalized content, and tailored class recommendations (e.g., more yoga sessions for low-intensity groups). It also enables users to connect with others who share similar workout routines, eating habits, or fitness goals, fostering a supportive community.

Personalized Workout Recommendations (Collaborative Filtering)
Goal: To provide real-time, personalized workout suggestions to users based on similarities with other users.
Methodology: We built a recommendation system using the K-Nearest Neighbors (KNN) algorithm. When a new user inputs their information (age, gender, height, weight, stress level, preferred workout duration), the system identifies the most similar existing users. It then recommends the top three workout activities most frequently performed by those similar users.
Application: This functionality is showcased through an interactive web application built with Streamlit, allowing users to receive instant, tailored exercise suggestions.

3. Application: Interactive Workout Recommender
To demonstrate the practical application of our data mining models, we developed a user-friendly interface using the Streamlit library. This web form allows users to input their personal details and instantly receive their top three personalized workout recommendations. This simulation highlights how the system can provide real-time, data-driven suggestions. Additionally, the application can classify users as "At Risk" or "Retained" and show them which cluster they belong to, providing valuable insights for both users and business owners.

Technologies Used
Programming Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn (StandardScaler, KMeans, RandomForestClassifier, TSNE, PCA)

Imbalanced Data Handling: imblearn (SMOTE)

Data Visualization: Matplotlib, Seaborn

Web Application Framework: Streamlit

Database: PostgreSQL (for Data Warehouse)

ETL Tool: Pentaho

Business Intelligence & Visualization: Tableau

Dataset
The project utilizes the "FitLife Health & Fitness Tracking Dataset" from Kaggle, which contains comprehensive fitness tracking data, including demographic information, activity metrics, health indicators, and lifestyle metrics for various participants.

Kaggle Dataset Link