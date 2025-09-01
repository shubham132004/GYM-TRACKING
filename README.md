# GYM-TRACKING
# 🏋️‍♂️ Gym Tracking – Predicting Calories Burned with KNN  

## Project Overview  
This project applies the **K-Nearest Neighbors (KNN)** algorithm to a **Gym Members Exercise Tracking dataset**.  
The primary objective is to **predict calories burned** based on various exercise-related features such as duration, intensity, and other physical parameters.  

Through this project, I explored:  
- How KNN behaves with different values of **K**  
- The impact of **distance metrics** on performance  
- Model evaluation using **error metrics** like MSE, RMSE, and MAE  
- Visualization of results for better interpretation  

---

## Tech Stack  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## Dataset  
- **Source:** `gym_members_exercise_tracking.csv`  
- **Target Variable:** `Calories Burned`  
- **Features:** Includes exercise-related details such as duration, weight, height, and intensity.  

---

## Workflow  
1. **Data Preprocessing**  
   - Checked for null values and cleaned the dataset  
   - Performed feature scaling to improve KNN performance  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots of features  
   - Correlation analysis  
   - Outlier detection  

3. **Model Implementation (KNN)**  
   - Tested multiple values of **K**  
   - Applied different distance metrics (Euclidean, Manhattan, Minkowski)  
   - Compared model performance  

4. **Evaluation Metrics**  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - Mean Absolute Error (MAE)  

---

## Results  
- Found the optimal **K value** through hyperparameter tuning  
- Observed trade-offs between bias and variance for small vs. large K  
- Highlighted why **KNN is not always suitable for production** due to high prediction time and memory cost  

---

## How to Run  
1. Clone the repository:
   - https://github.com/shubham132004/GYM-TRACKING
2. Install dependencies:
   - pip install -r requirements.txt
3. Run the Jupyter Notebook 
   ```bash
