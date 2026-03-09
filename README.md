# Forest Fire Prediction using Linear Regression

Overview
This project predicts the burned area of forest fires using weather and environmental variables from Montesinho Natural Park, Portugal. It demonstrates a complete data science workflow: EDA, cleaning, and modeling.

Dataset
The dataset contains 517 observations of environmental variables such as temperature, humidity, wind, and fire weather indices. The target variable is the burned area, which was log-transformed to reduce skewness.

 Project Structure
- data/forestfires_clean.csv
- notebooks/explore.ipynb
- notebooks/clean.ipynb
- notebooks/model.ipynb
- README.md

Data Cleaning & Preprocessing
- Removed duplicate rows
- Applied log transformation to the target variable
- Encoded categorical variables (month and day) using one-hot encoding
- Scaled numerical features using StandardScaler

Modeling
A Linear Regression model was trained on 80% of the dataset and evaluated on 20% of the data. The model predicts log-transformed burned area based on the weather and fire index variables.

Results
The model achieved reasonable performance given the high variability in fire sizes. Evaluation metrics (RMSE and R²) indicate that the model captures some relationships between environmental variables and burned area, but extreme fires remain difficult to predict.
