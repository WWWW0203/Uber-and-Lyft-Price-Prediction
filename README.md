# Uber-and-Lyft-Price-Prediction

With the popularity of Uber and Lyft services expanding across the United States, recognizing how prices change under different circumstances provides valuable insights and helps individuals plan their travel ahead of time. The goal of this project is to develop regression models to predict ride prices for Uber and Lyft based on features such as distance traveled, weather, time of day, etc. Since neither Uber nor Lyft publicly releases their data, the dataset was obtained from [Kaggle]([https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices/data]). The dataset’s author collected real-time data using Uber & Lyft API queries and corresponding weather conditions in a few hotspots in Boston for over a week from Nov. 18, 2018. Random Forest attained a best mean score of 96% R-Squared value.


The project is built in Python 3.11.4 and repository organization is as follows:
1. `data/` - Stores all raw data files.
2. `figures/` - Store all the figures, diagrams, and table from the EDA stage to the result stage
3. `results/` - Stores the result of five models and the metrics (RMSE and R Sqared) associated with each model.
4. `report/` - Summary reports, and presentation slides.
5. `src/` - Code generated the process from beginning to end.


The key packages used in this project are the following:
- pandas=2.0.3
- matplotlib=3.7.2
- numpy=1.24.4
- seaborn=0.12.2
- python=3.11.4
- py-xgboost=1.7.6
- scikit-learn=1.3.0
- shap=0.42.1
