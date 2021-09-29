# Airline-Customer-Satisfaction-Prediction
 Machine learning application procuring CRISP-DM methodology is implemented to derive an appropriate solution for a business problem undertaking six phases - Business understanding, Data understanding, Data preparation, Data Modelling, Evaluation and Deployment.
## Objective
The objective of performing this project is to assist an airline firm in determining the key aspects that influence customer or passenger satisfaction. Customer satisfaction has a significant impact on a company's operations, thus analysing and enhancing the contributing features that are directly associated to customer satisfaction is critical for a organizations growth and reputation. <br/>
## Data Description
The dataset for this project is obtained from Kaggle which contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. The dataset consists of 23 columns such as Age, Gender, Travel class, Arrival and Departure delays and also features that influences customer satisfaction level such as On-board service, Cleanliness, Seat comfort, Baggage handling and many more. <br/>
The dataset consists of a column or feature named ***‘satisfaction’*** which describes the overall satisfaction level of the customer. It has two values, ‘dissatisfied’ and ‘satisfied’. This ***satisfaction*** feature is considered as the label/dependent feature since it conveys the overall experience of the customer based on the ratings provided for other features. The dataset consists of 129881 records. <br/> Source dataset: https://www.kaggle.com/sjleshrac/airlines-customer-satisfaction
## Data Pre-processing and Visualisation
Data cleaning plays a key role in deriving the output of a machine learning model. Usually data cleaning consists of processes like determining outliers and removing or imputing outliers, removing or replacing missing values, removing duplicate values, removing values with less or no importance. <br/>
In this project, the *‘Arrival Delay in Minutes’* column has 393 missing values in it and will be handled.
<br/>
Data Visualisation plays an important role in understanding the data as it gives an overview of the data before the model implementation. Exploratory Data Analysis is done for the dataset to gather unrecognized information and comprehend information with ease.
## Feature Selection
Correlation among the features are found by generating a correlation heat map. The importance of features are determined using statistical techniques.
## Models
Three models were compared to check for maximum efficiency based on researching related works. They are,

- KNN
- Decision Tree
- Random Forest
## Evaluation Metrics
- Accuracy
- ROC Curve
- Time Taken
- Confusion Matrix
- Classification Report

## Conclusion
Random Forest and Decision Tree have performed equally and produced high ROC_AUC score (~95%). But ***Random Forest*** took lesser amount of time compared to time taken by Decision Tree. Therefore, we can conclude that Random Forest as the best model. <br/>
