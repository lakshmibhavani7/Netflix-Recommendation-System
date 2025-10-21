# Netflix-Recommendation-System
Netflix Recommendation System predicting user preferences and suggesting movies using collaborative filtering in Python.

# 🎬 Netflix Recommendation System using SVD

## 📘 Overview
This project builds a personalized recommendation system that predicts user ratings for unseen movies using **Singular Value Decomposition (SVD)** — a collaborative filtering approach. The goal is to enhance user engagement by providing accurate and relevant content suggestions.

## 🎯 Objective
To design a recommendation model that suggests movies to users based on their past preferences, improving user experience and retention.

## 🧠 Approach
- Loaded and preprocessed the **Netflix movie ratings dataset**.  
- Conducted **exploratory data analysis (EDA)** to understand user–movie interactions and rating trends.  
- Applied **SVD-based matrix factorization** using the **Surprise** library to predict unknown ratings.  
- Evaluated model performance using **RMSE (Root Mean Square Error)** and visualized rating distributions.

## 🧰 Tools & Technologies
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Surprise  
- **Techniques:** Collaborative Filtering, Matrix Factorization (SVD), Recommender Systems  

## 📊 Key Insights
- The SVD model efficiently captured user–item relationships, improving prediction accuracy.  
- Users with consistent rating behavior contributed more to model stability.  
- Discovered how recommendation accuracy varies across genres and activity levels.

## 🚀 Results
- Achieved a **low RMSE value**, indicating reliable prediction performance.  
- Generated personalized movie recommendations for individual users.  
- Demonstrated the potential of matrix factorization for large-scale recommendation systems.

## 📂 Files in Repository
- `Netflix_recommendation_system.ipynb` – Jupyter notebook with code, visualizations, and analysis.  
- `README.md` – this documentation.  

## 📈 Visualization
- Rating distribution graphs.  
- Actual vs. Predicted rating plots.  
- User recommendation samples generated from the trained model.

## 🧩 Future Work
- Integrate **content-based filtering** to enhance hybrid recommendations.  
- Deploy model via **Streamlit** for interactive recommendation demos.

---

**🔗 Connect with Me:**  
I’d love to collaborate or discuss ways to enhance recommendation systems — feedback is always welcome!

