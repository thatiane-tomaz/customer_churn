<!-- PROJECT LOGO -->
  <h2 align="center">Customer Churn Prediction</h2>

  <p align="center">


<!-- ABOUT THE PROJECT -->
### About The Project
Customer Churn happens when customers decide to not continue purchasing products/services from an organization and end their association. Avoiding this event is a very important strategy of the most successful companies, as the costs are related to lose recurring earnings and lose expansion opportunity. Besides, it is much more difficult and expensive to attract a new customer than to retain the one that was already been attracted.
This script is for Customer Churn Prediction, comparing the results of Random Forest Classifier, Logistic Regression and Gradient Boosting with different hyperparameter values.

### Getting Started

It was used Anaconda (Python 3.8) and the following packages:
- pandas
- numpy
- matplotlib
- scikit learn


### Data

The dataset used for training the model was downloaded from Kaggle and is available in the folder "data" in this repository.


### Code Steps
#### Preprocessing

During the preprocessing and feature engineering stage the database was prepared to be used in model training. 
* Creation of new columns of square Estimated Salary ans Balance.

#### Model Training

The classification was trained using GridSearchCV to find the best hyperparameters and Pipeline to find the best model using accuracy as comparison factor.
The Pipeline was also used to choose the number of features with Principal Component Analysis (PCA). 


#### Results

The results showed that the Random Forest model presents the best accuracy. However, it is possible to notice that the model recall is low, so it is necessary to analyze the ROC Curve and define a trade-off between True and False Positives that are in line with the company's strategy.




### Conclusions
The model proved to be useful to assist in decisions related to customer retention. However, some improvements are still needed, such as the analysis of better features for the model and testing of other libraries and hyperparameters to improve the recall.


<!-- CONTRIBUTING -->
### Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.



<!-- LICENSE -->
### License

Distributed under the MIT License. See `LICENSE` for more information.
