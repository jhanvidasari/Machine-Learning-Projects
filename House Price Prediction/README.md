# California Housing Price Prediction
This file contains code for predicting house prices using three different models: 
- **Neural Network**
- **Decision Tree Regressor**
- **Linear Regression**

Dataset: California Housing dataset.


## Dataset
The California Housing dataset consists of features such as:

* MedInc: Median income in block group
* HouseAge: Median house age in block group
* AveRooms: Average number of rooms per household
* AveBedrms: Average number of bedrooms per household
* Population: Block group population
* AveOccup: Average number of household members
* Latitude: Block group latitude
* Longitude: Block group longitude

The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars.

## Models
### Neural Network
  - Implemented using Keras.
  - Mean Absolute Error: 0.9304

### Decision Tree Regressor
  - Implemented using Scikit-learn.
  - Mean Absolute Error: 0.4628

### Linear Regression
  - Implemented using Scikit-learn.
  - Mean Absolute Error: 0.5351

## Requirements
To run the code, you need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn
- keras
You can install the necessary libraries using pip:
```
pip install pandas numpy scikit-learn keras
```

## Conclusion
Among the three models, the Decision Tree Regressor yielded the lowest Mean Absolute Error, followed by Linear Regression and then the Neural Network.
