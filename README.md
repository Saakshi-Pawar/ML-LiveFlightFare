<h1>Flight Fare Prediction – Machine Learning Project</h1>

<h3>Overview</h3>

This project predicts the price of a flight ticket using Machine Learning.
Different factors like airline, source, destination, duration, total stops and journey time are used to estimate the final ticket fare.

The goal is to understand what affects flight prices and build an accurate prediction model that can help users make better booking decisions.

<h3>Tools & Technologies Used</h3>
<ul>
<li>Python</li>

<li>Pandas</li>

<li>NumPy</li>

<li>Matplotlib</li>

<li>Scikit-learn</li>

<li>Jupyter Notebook</li>
</ul>

<h3>Dataset Information</h3>

The dataset contains the following important columns:
<ul>
<li>Airline</li>

<li>Date of Journey</li>

<li>Source</li>

<li>Destination</li>

<li>Route</li>

<li>Departure Time</li>

<li>Arrival Time</li>

<li>Duration</li>

<li>Total Stops</li>

<li>Additional Info</li>

<li>Price (Target Variable)</li>
</ul>

The dataset is pre-processed and cleaned before training the model.

<h3>Methodology</h3>

**1. Data Loading**
<ul>
<li>Loaded the dataset using pandas.read_excel()</li>
</ul>

**2. Data Cleaning**
<ul>
<li>Handled missing values</li>

<li>Removed unnecessary columns: Route and Additional_Info</li>
</ul>

**3. Feature Engineering**

Extracted:
<ul>
<li>Journey Day & Month</li>

<li>Departure Hour & Minute</li>

<li>Arrival Hour & Minute</li>

<li>Converted Duration into hours and minutes</li>
</ul>

**4. Encoding**

Applied One-Hot Encoding for categorical features:
<ul>
<li>Airline</li>

<li>Source</li>

<li>Destination</li>
</ul>

**5. Feature Selection**

Used Random Forest feature importance to select important features


**6. Model Building**

Trained multiple ML models:
<ul>
<li>Decision Tree</li>

<li>KNN</li>

<li>Random Forest</li>

<li>Support Vector Regression (SVR)</li>
</ul>

**7. Best Model Selection**

Compared results and selected the Random Forest model for final prediction

<h3>Conclusion</h3>

Different models were tested, and the Random Forest model performed the best in terms of prediction accuracy. Feature engineering played a critical role in improving performance. The model can help users estimate ticket prices before booking their flights.
