# Stress Level Prediction Using Sleep and Physiological Data

## Project Overview
This project explores the relationship between physiological metrics (e.g., heart rate, blood oxygen levels) and stress levels during sleep. Using machine learning techniques, the goal is to predict stress levels and identify key factors contributing to stress.

## Research Question
**How accurately can stress levels during sleep be predicted, and which physiological factors play the most significant role in these predictions?**

## Motivation
Understanding stress predictors can help design better sleep and lifestyle interventions. This project aims to provide insights into how physiological data affects stress levels and proposes actionable recommendations for stress management.

## Dataset
- **Dataset Name:** SaYoPillow Dataset
- **Source:** Kaggle ([Dataset Link](https://www.kaggle.com/datasets/laavanya/human-stress-detection-in-and-through-sleep))
- **Description:** The dataset includes metrics like snoring range, heart rate, hours of sleep, and stress levels categorized into 5 levels (0: Low, 4: High).

## Files in This Repository
- `sleep_prediction_code.ipynb`: Jupyter notebook containing the entire workflow, including:
  - Data Cleaning and Preprocessing
  - Exploratory Data Analysis (EDA)
  - Feature Engineering
  - Model Training and Evaluation
  - Insights and Recommendations
- `README.md`: Documentation of the project, including an overview, methodology, and results.
- `data/`: Folder containing the dataset used for analysis.

## Libraries Used
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for visualizations
- `scikit-learn` for machine learning models
- `numpy` for numerical operations

## Results
1. **Key Predictors of Stress:**
   - **Positive Correlations:** Snoring Range, Heart Rate, Limb Movement Rate
   - **Negative Correlations:** Blood Oxygen Level, Hours of Sleep

2. **Model Accuracy:**
   - **Random Forest (Train-Test Split):** 98%
   - **Gradient Boosting:** 98%
   - **Random Forest with K-Fold Cross-Validation:** 
     - Mean Accuracy: 99.05%
     - Standard Deviation: 0.93%
    
![Screenshot 2024-12-27 231635](https://github.com/user-attachments/assets/f0dae6bf-0c82-4d6c-9887-4ba7b6725db3)

![Screenshot 2024-12-27 231624](https://github.com/user-attachments/assets/53cdc416-a901-4bce-8600-ad3261b85d9f)

![Screenshot 2024-12-27 231652](https://github.com/user-attachments/assets/60fd0aa6-8c8a-4247-835e-98d3429cf2c6)


3. **Insights:**
   - Physiological features like heart rate and snoring range are strong predictors of high stress levels.
   - Longer sleep durations and better oxygen levels are associated with lower stress.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/noorAlsaud/sleep_prediction.git
