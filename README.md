#  Predicting Optimal Fertilizers  
*Kaggle Playground Series — Season 5, Episode 6*  
 *College Assignment Project (2025)*

---

##  Project Overview  
This project was developed as part of our **academic assignment**.  
We participated in the **Kaggle Playground Series 2025 (Season 5, Episode 6)** — *Predicting Optimal Fertilizers* — to apply and strengthen our machine learning skills.  

The goal is to **predict the best fertilizer** for given soil, crop, and weather conditions using supervised machine learning models.

---

##  Team Members
- [**Boreddy Supriya Reddy**](https://github.com/BSupriyaReddy31)  
- [**Pattikonda Surendra**](https://github.com/surendrapattikonda)

---

##  Objective  
To build a machine learning model that predicts **the optimal fertilizer combination** for different weather, soil, and crop conditions using data provided by Kaggle.

---


---

##  Dataset  
- **Source:** [Kaggle Competition Link](https://www.kaggle.com/competitions/playground-series-s5e6)  
- **Files Used:**
  - `train.csv` — Training dataset  
  - `test.csv` — Test dataset  
  - `sample_submission.csv` — Submission format  

The dataset is **synthetically generated** to simulate real-world agricultural conditions (soil composition, weather, crop type, etc.) while protecting private data.

---

##  Approach  
1. **Exploratory Data Analysis (EDA):**  
   - Studied feature distributions and relationships.  
   - Checked missing values and outliers.  
2. **Feature Engineering:**  
   - Encoded categorical variables.  
   - Created interaction terms between soil and weather features.  
3. **Modeling:**  
   - Trained **LightGBM**, **XGBoost**, and **CatBoost** models.  
   - Combined them using a **Voting Classifier** ensemble.  
4. **Evaluation:**  
   - Optimized models based on **MAP@3** performance.  

---

##  Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, LightGBM, XGBoost, CatBoost  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

##  Notebooks

- **EDA Notebook:** [EDA.ipynb](notebooks/EDA.ipynb)  
  Exploratory Data Analysis and feature exploration.

- **Modeling Notebook:** [Modeling.ipynb](notebooks/Modeling.ipynb)  
  Model training, tuning, and evaluation.
---

##  Results
- **Best Model:** Voting Ensemble (LightGBM + XGBoost + CatBoost)  
- **Submission File:** [`results/submission.csv`](results/submission.csv)  

---

##  Assignment Details  
- **Mentor:** Dr. P. Penchal Prasad
- **Institution:** RGM College of Engineering and Technology  
- **Purpose:** Submitted for semester assignment marks and external evaluation as part of the Kaggle Playground Series competition.

---

## Future Work
- Integrate real-time soil and weather data for dynamic predictions.  
- Develop a web interface for farmers to receive fertilizer recommendations interactively.  
- Experiment with deep learning and feature importance analysis for improved accuracy.

---
  

Special thanks to our **faculty and mentor** for their continuous guidance and feedback.

---

⭐ **If you like this project, don't forget to star the repository!**

