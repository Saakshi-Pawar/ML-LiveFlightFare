# Flight Fare Prediction – Machine Learning Project

### Overview

This project predicts the price of a flight ticket using Machine Learning.
Different factors like airline, source, destination, duration, total stops and journey time are used to estimate the final ticket fare.

The goal is to understand what affects flight prices and build an accurate prediction model that can help users make better booking decisions.

### Tools & Technologies Used

1. Python

2. Pandas

3. NumPy

4. Matplotlib

5. Scikit-learn

6. Jupyter Notebook


### Dataset Information

The dataset contains the following important columns:

1. Airline

2. Date of Journey

3. Source

4. Destination

5. Route

6. Departure Time

7. Arrival Time

8. Duration

9. Total Stops

10. Additional Info

11. Price (Target Variable)

The dataset is pre-processed and cleaned before training the model.

### Methodology

#### 1. Data Loading

Loaded the dataset using pandas.read_excel()


#### 2. Data Cleaning

Handled missing values

Removed unnecessary columns: Route and Additional_Info


#### 3. Feature Engineering

Extracted:

Journey Day & Month

Departure Hour & Minute

Arrival Hour & Minute

Converted Duration into hours and minutes


#### 4. Encoding

Applied One-Hot Encoding for categorical features:

Airline

Source

Destination


#### 5. Feature Selection

Used Random Forest feature importance to select important features


#### 6. Model Building

Trained multiple ML models:

Decision Tree

KNN

Random Forest

Support Vector Regression (SVR)


#### 7. Best Model Selection

Compared results and selected the Random Forest model for final prediction

### Conclusion

Different models were tested, and the Random Forest model performed the best in terms of prediction accuracy. Feature engineering played a critical role in improving performance. The model can help users estimate ticket prices before booking their flights.
