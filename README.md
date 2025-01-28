# California Housing Price Prediction

This project uses the California Housing dataset to predict housing prices using various regression models. The dataset is preprocessed, and models are evaluated based on key metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared Score (R²).

## Features
The dataset includes the following features:
- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average number of occupants per household
- `Latitude`: Block group latitude
- `Longitude`: Block group longitude

The target variable is the median house price in the block group.

---

## Project Workflow
1. **Data Loading and Preprocessing**:
   - Load the California Housing dataset.
   - Handle missing values.
   - Standardize the features using `StandardScaler`.

2. **Data Splitting**:
   - Split the data into training (80%) and testing (20%) sets.

3. **Model Implementation**:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor (SVR)

4. **Model Evaluation**:
   - Evaluate models using:
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)
     - R-squared Score (R²)
   - Compare the performance of all models.

---

## Results
The performance of the models is displayed using the following metrics:

### Mean Squared Error (MSE):
- **Linear Regression**: `<value>`
- **Decision Tree Regressor**: `<value>`
- **Random Forest Regressor**: `<value>`
- **Gradient Boosting Regressor**: `<value>`
- **SVR**: `<value>`

### Mean Absolute Error (MAE):
- **Linear Regression**: `<value>`
- **Decision Tree Regressor**: `<value>`
- **Random Forest Regressor**: `<value>`
- **Gradient Boosting Regressor**: `<value>`
- **SVR**: `<value>`

### R-squared Score (R²):
- **Linear Regression**: `<value>`
- **Decision Tree Regressor**: `<value>`
- **Random Forest Regressor**: `<value>`
- **Gradient Boosting Regressor**: `<value>`
- **SVR**: `<value>`

---

## License
This project is licensed under the MIT License.

