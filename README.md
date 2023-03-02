# California Housing Price Prediction Model
This project is a machine learning model that predicts housing prices in California using data from Kaggle's California Housing Prices dataset. The model was built using both linear regression and random forest models, with the random forest model achieving better accuracy.

<h1>Technologies Used</h1>
Python
Jupyter Lab
Scikit-learn

# Getting Started
To run this project on your own machine, follow these steps:

Clone the repository onto your local machine.
Install the required dependencies using pip install -r requirements.txt.
Open the housing_price_prediction.ipynb notebook in Jupyter Lab.
Follow the instructions in the notebook to load and preprocess the data, build and train the linear regression and random forest models, and evaluate their performance.
Data Preprocessing
The dataset contained missing values, which were imputed using the mean value of the feature. Additionally, the features were scaled using Scikit-learn's StandardScaler to ensure that all features were on a similar scale.

Model Selection
Both linear regression and random forest models were trained and evaluated on the dataset. The random forest model achieved better accuracy, with a mean absolute error of 50,000 USD compared to the linear regression model's mean absolute error of 80,000 USD.

Conclusion
This project demonstrates how machine learning models can be used to predict housing prices using real-world data. By comparing the performance of linear regression and random forest models, we were able to identify the best model for this particular dataset.
