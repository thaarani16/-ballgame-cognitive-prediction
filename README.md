# Ball Counting Game - Machine Learning Based Cognitive Performance Prediction

This project explores the application of supervised machine learning techniques to predict cognitive performance based on participants' interaction with a logic-based color ball game. The game involves drawing colored balls, computing scores, and reporting results under time constraints. The time taken to solve tasks forms the basis for performance prediction.

The work is part of an internship project at **NIT Trichy** and is also being submitted as a conference research paper.

---

## 📂 Dataset

The dataset contains records from **10 participants**, each performing **20 cycles**, where times to complete tasks with 2, 3, 4, and 5 balls were recorded.  

**Features:**
- `Person` - Participant ID (P1 to P10)  
- `Time_2` - Time for solving 2-ball task (seconds)  
- `Time_3` - Time for solving 3-ball task (seconds)  
- `Time_4` - Time for solving 4-ball task (seconds)  
- `Time_5` - Time for solving 5-ball task (seconds)  

---

## 📊 Methodology

Seven machine learning regression models were implemented to predict the time for the 5-ball task:

- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor
- XGBoost Regressor
- LightGBM Regressor
- k-Nearest Neighbors (KNN) Regressor

**Evaluation Metrics:**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🏆 Best Performing Model

Based on experimental results, the **Decision Tree Regressor** demonstrated the most consistent performance in predicting cognitive task completion times, achieving an average accuracy of approximately **94.89%**, as detailed in the research draft.

This highlights the Decision Tree model's effectiveness in capturing patterns within behavioral time data for cognitive performance estimation.
