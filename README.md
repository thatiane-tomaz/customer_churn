<!-- PROJECT LOGO -->
  <h2 align="center">Customer Churn Prediction</h2>

  <p align="center">


<!-- ABOUT THE PROJECT -->
### About The Project
  
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


#### Results and Conclusions

The results showed that the Random Forest model presents the best accuracy. However, it is possible to notice that the model recall is low, so it is necessary to analyze the ROC Curve and define a trade-off between True and False Positives that are in line with the company's strategy.



<!-- CONTRIBUTING -->
### Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.




<!-- LICENSE -->
### License

Distributed under the MIT License. See `LICENSE` for more information.
