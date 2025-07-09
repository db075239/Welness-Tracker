# 💪 Wellness Tracker: Data-Driven Health & Fitness Insights

This project leverages **data analytics** and **machine learning** to deliver valuable insights from health and fitness data—aiming to boost user engagement and help users stay committed to their wellness journey.

We developed a comprehensive system combining:

- 📊 In-depth data analysis  
- 🤖 Predictive modeling  
- 👥 User segmentation  
- 🧠 Personalized workout recommendation system  

---

## 📌 Project Overview

Our primary objective was to extract **actionable insights** and **patterns** from a health and fitness dataset, empowering users and providing value to stakeholders in the wellness industry.

We applied:

- **Descriptive Analytics** – for data exploration and visualization  
- **Data Mining Techniques** – including classification, clustering, and collaborative filtering  

---

## 🔍 1. Data Analysis: Unveiling Fitness Benefits

We explored how fitness and lifestyle variables interact across various dimensions like demographics, health indicators, and behaviors.

### Key Insights

- **Workout Trends:** Activity types across age, gender, and BMI  
- **Activity Effectiveness:** Activities ranked by average calories burned  
- **Lifestyle Impact:** Effects of smoking on sleep, stress, and exercise  
- **Demographic Influence:** How age and gender affect workout intensity and steps  
- **Health Correlations:** BMI vs. fitness, stress vs. blood pressure, hydration vs. heart rate  
- **Daily Steps Patterns:** Average steps by age group and stress level  

👉 _These insights form the backbone of our app’s logic and validate its necessity._

📊 **Interactive Dashboard:**  
> View insights via our [Tableau Public Dashboard](https://public.tableau.com/app/profile/david.blazheski/vizzes)

---

## 🤖 2. Data Mining: Predictive Insights & Personalization

### 🔐 User Churn Prediction (Classification)

- **Goal:** Predict which users are likely to stop using the app or unsubscribe  
- **Algorithm:** `RandomForestClassifier`  
- **Technique:** Handled class imbalance using `SMOTE`  
- **Features:** Activity frequency, sleep quality, stress levels, etc.  

✅ Helps businesses intervene early to retain users.

---

### 👤 User Segmentation (Clustering)

We used clustering to identify user archetypes based on their habits:

#### 📈 First Attempt:
- Based only on workout intensity → **Poor separation**

#### ✅ Refined Clustering:
Based on age, BMI, sleep, calories burned, hydration, stress, steps, etc.

**Identified Segments:**

1. **Young, High-Activity Users** – Ideal for performance-focused programs  
2. **Older, Consistent Exercisers** – Suitable for endurance routines  
3. **Older, Low-Activity Users** – Best served by beginner-friendly plans  
4. **Young, Inefficient Exercisers** – Need structured training and stress management  

✅ Enables targeted recommendations, ads, and community features.

---

### 🧠 Personalized Workout Recommendations (Collaborative Filtering)

- **Goal:** Suggest workouts based on similar users  
- **Algorithm:** `K-Nearest Neighbors (KNN)`  
- **Input:** Age, gender, height, weight, stress level, workout duration  
- **Output:** Top 3 workouts most frequently done by similar users  

🎯 Powering real-time personalization.

---

## 💻 3. Application: Interactive Workout Recommender

We built a web app using **Streamlit** that allows users to:

- Input personal info (age, gender, fitness level, etc.)  
- Receive **personalized workout suggestions**  
- See their **churn status** and **cluster type**  

🌐 _Bridging ML with user experience in real time!_

---

## 🧰 Technologies Used

| Category                 | Tools/Frameworks                                           |
|--------------------------|------------------------------------------------------------|
| **Programming Language** | Python                                                     |
| **Data Manipulation**    | Pandas, NumPy                                              |
| **Machine Learning**     | Scikit-learn (`StandardScaler`, `KMeans`, `RandomForest`), TSNE, PCA |
| **Imbalanced Data**      | `imblearn` (SMOTE)                                         |
| **Visualization**        | Matplotlib, Seaborn                                        |
| **Web App**              | Streamlit                                                  |
| **Database**             | PostgreSQL (Data Warehouse)                                |
| **ETL Tool**             | Pentaho                                                    |
| **BI Dashboard**         | Tableau                                                    |

---

## 📂 Dataset

We used the **FitLife Health & Fitness Tracking Dataset** from Kaggle, containing rich data on:

- Demographics  
- Activity metrics  
- Health indicators  
- Lifestyle factors  

🔗 [Kaggle Dataset – FitLife Health & Fitness Tracking](https://www.kaggle.com/datasets/ganeshkumar269/fitlife-health-fitness-tracking)

---

## 🚀 Project Highlights

- 📉 Reduced churn through predictive analytics  
- 🧬 Identified behavioral patterns via clustering  
- 🏋️ Delivered personalized workout plans  
- 📈 Empowered business strategies with actionable insights  
- 💡 Delivered everything through an interactive, intuitive web interface  

---

