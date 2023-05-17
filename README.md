# WildBlueberryYieldPrediction
Wild blueberry yield prediction using ensemble of LightGBM and CatBoost. Other models like XGBoost and Neurale Networks where tested but underperformed compared to LightGBM and CatBoost.

Dataset features:
- **clonesize**: The average blueberry clone size in the field (m²).
- **honeybee**: The honeybee density in the field (bees/m²/min).
- **bumbles**: The bumblebee density in the field (bees/m²/min).
- **andrena**: The Andrena (mining bee) density in the field (bees/m²/min).
- **osmia**: The Osmia (mason bee) density in the field (bees/m²/min).
- **MaxOfUpperTRange, MinOfUpperTRange, AverageOfUpperTRange**: Maximum, minimum, and average of the upper temperature range (℃) during the growing season.
- **MaxOfLowerTRange, MinOfLowerTRange, AverageOfLowerTRange**: Maximum, minimum, and average of the lower temperature range (℃) during the growing season.
- **RainingDays**: The total number of days with precipitation larger than zero during the bloom season (Days).
- **AverageRainingDays**: The average of raining days of the entire bloom season (Days).
- **fruitset**: The percentage of flowers that develop into mature fruit.
- **fruitmass**: The average mass of a single fruit.
- **seeds**: The average number of seeds per fruit.

Kaggle Competition: https://www.kaggle.com/competitions/playground-series-s3e15  
Kaggle Notebook: https://www.kaggle.com/code/mnokno/ps3e15-eda-imputation-using-mice  
