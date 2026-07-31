# Boston House Price Prediction

## Project Objective

The objective of this project is to develop a machine learning regression model capable of predicting Boston housing prices based on several economic and housing-related attributes.

---

## Dataset

The dataset contains various housing characteristics including:

- Crime Rate
- Number of Rooms
- Age of Property
- Distance from Employment Centers
- Property Tax Rate
- Pupil-Teacher Ratio
- Other Socioeconomic Features

Target Variable:

- House Price

---

## Workflow

### Data Preprocessing

- Loaded dataset into Pandas DataFrame
- Checked missing values
- Verified data consistency
- Prepared features and target variables

---

### Exploratory Data Analysis

Performed:

- Statistical Summary
- Correlation Matrix
- Feature Inspection

---

### Model Selection

The project utilizes:

- XGBoost Regressor

XGBoost provides excellent performance for structured tabular datasets and effectively captures nonlinear relationships.

---

### Model Training

The dataset was divided into training and testing datasets before training the regression model.

---

### Evaluation

Performance was evaluated using:

- R² Score
- Mean Squared Error (MSE)

These metrics help determine prediction accuracy.

---

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## Future Improvements

- Hyperparameter Optimization
- Cross Validation
- Feature Selection
- Model Deployment using Flask or FastAPI

---

## Conclusion

The implemented regression model successfully predicts housing prices with good accuracy and demonstrates the effectiveness of machine learning in real estate price estimation.
