# 🚲 Optimization of Urban Bike-Sharing Station Locations

## 📌 Project Overview
As part of the **Healthy Mobility Culture of Seoul Project**, this predictive analysis project aims to identify the optimal hub locations for Seoul's public bicycle system, "Ttareungi"(따릉이). 
By leveraging machine learning techniques on public urban mobility datasets, the goal is to provide data-driven strategies that improve urban transportation efficiency, reduce carbon emissions, and promote overall community health.

## 📊 Data & Preprocessing
*  **Dataset:** Seoul Public Bicycle Usage Information (Jan-Jun 2023).
*  **Data Size:** Processed and refined the raw data into a robust dataset of **417,222 records** and 10 key features.
*  **Feature Engineering:** Analyzed correlations and utilized features including Rental Date/Month, Station ID, User Gender, Age Group, Usage Count, Exercise Volume, Carbon Reduction, and Travel Distance/Time.

## 🤖 Modeling & Optimization
 To predict high-demand hub locations, I developed and optimized an **XGBoost Classifier**. 
*  **Hyperparameter Tuning:** Utilized `GridSearchCV` with Cross-Validation (5-fold) to systematically find the optimal model parameters.
*  **Optimized Parameters:** Achieved the best performance with parameters such as `learning_rate=0.01`, `max_depth=4`, `min_child_weight=1`, and `n_estimators=400` using the `hist` tree method.
*  **Evaluation:** Evaluated the model using accuracy scores to ensure reliable predictions for future station deployments.

## 🚀 Business Impact & Future Directions
* **Urban Planning:** The predictive model provides actionable insights for city planners to strategically allocate bike-sharing stations in high-demand or underserved areas.
* **Community Health:** Encouraging public bicycle usage directly contributes to a healthier mobility culture and environmental sustainability.
* **Future Improvements:** Expanding the dataset to include weather conditions, nearby public transit nodes, and topological data to further enhance the classification accuracy.
