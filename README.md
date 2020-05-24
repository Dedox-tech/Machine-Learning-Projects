# Data Science Projects by Diego Murillo

This is my Data Science and Machine Learning collection of projects. Since I am business-related undergraduate student, I am really interested in show how Machine Learning can solve real-world business problems very well.
The projects stored in this repository are ordered by technical field. I am always learning Machine Learning for my own, so you can expect updates in the existing ones in a regular basis. Also I will add new projects as soon as I could.

## 1. Deep Learning

### 1.1 Predictive Maintenance on Hydraulic Systems 

The objective of this project is to predict if a petroleum-based Hydraulic System will fail in a time window given or will not fail. The system has 5 components but in this work we just examined three of them (cooler, pump and flag). Essentially, this is a predictive maintenance problem framed as a multi-class classification task. Therefore, we used a Deep Learning approach for handle the situation. As a methodology, we use Artificial Neural Networks (ANN). Specifically, we use Convolutional Neural Networks (CNN) for predicting this part. Since these are three targets (condition monitoring of the pump, condition monitoring of the cooler, condition monitoring of the flag), we utilize the same Neural Network architecture and finally trained three different models. The rate of implementation of predictive maintenance in manufacturing plants is increasing extremely worldwide. Recently companies seem to understand that Machine Learning systems could give better maintenance schedules that simples fixed rules. This fact could lead to relevant reductions in operational costs, so the impact in the business is rather evident. 

[NBViewer](https://nbviewer.jupyter.org/github/Dedox-tech/Machine-Learning-Projects/blob/master/Summarize_Maintenance.ipynb) [GitHub](https://github.com/Dedox-tech/Machine-Learning-Projects/blob/master/Summarize_Maintenance.ipynb)

### 1.2 Sales Forecasting in a Brazilian Logistic Company 

This project aims to predict the daily demand of sales of a Brazilian Logistic Company. We use the information of the last 5 days of sales, for estimate the next daily sales. The data includes 60 days of the company operations. Also, it includes various features as the date and the sub classification of sales (non-urgent, urgent, type A, type B, type C). For modeling this phenomenon, we use Artificial Neural Networks (ANN). Specifically, we use a Multi-Layer Perceptron (MLP) as a baseline model. On the other hand, we use a Long Short-Term Memory (LSTM) Neural Network for trying to beating the performance of the baseline. The former Neural Network is very useful when we dealing with temporal data such as this dataset. Sales Forecasting is a typical operation management problem. Traditional approaches (time series forecasting) might include Econometrics and Statistical models such as SMA ARIMA etc. Although in real application these techniques work fairly well, it is worth exploring new approaches such the present, in order to improve the accuracy of the forecasting and enhancing the operational planning. 

[NBViewer](https://nbviewer.jupyter.org/github/Dedox-tech/Machine-Learning-Projects/blob/master/Sales_LSTM.ipynb) [GitHub](https://github.com/Dedox-tech/Machine-Learning-Projects/blob/master/Sales_LSTM.ipynb)

## 2. Machine Learning 

### 2.1 Prediction of the Effectiveness of a Marketing Campaign 

The objective of this project is to predict the success of a telemarketing campaign of a Portuguese bank. The marketing campaign is a phone call one. Essentially, an operator makes a phone to a client and then the operator asks to him/her if would like to subscribe to a product (bank term deposit). The answer is a binary option (yes or no). As a methodology, we use Ensemble of Decision Tree methods. We choice a simple Decision Tree (CART model), as a baseline model and other three Ensembles Decision Trees algorithms for trying to beating the performance of the baseline. Random Forest, Extremely Random Forest and Extreme Gradient Boosting were the algorithms chosen. If we can predict this event, we will save money and man-hours effort just calling to the ones with at least an acceptable/high probability of subscription. Also we can identify the most correlated features with this event, and using the knowledge for improving operational efficiency.

[NBViewer](https://nbviewer.jupyter.org/github/Dedox-tech/Machine-Learning-Projects/blob/master/marketing_analysis.ipynb) [GitHub](https://github.com/Dedox-tech/Machine-Learning-Projects/blob/master/marketing_analysis.ipynb)

### 2.2 Real Estate Valuation in the Taiwan Market 

The present project aims to predict the house prices at the Taiwan market. Given features as house ages, the number of convenience stores in the living circle and the distance to the nearest MRT (Mass Rapid Transit Aka Public Transportation), the goal is predicting the house price (measured as house price per unit area). As a methodologic approach, we use Advanced Regression Models for this task. We choice a Linear Regression as a baseline model. On the hand, we use six types of advanced regressions: Ridge Regression, Lasso Regression, Bayesian Regression, Bayesian Ridge Regression, Bagging Regression and AdaBoost Regression. Using Machine Learning models in Real State Valuation problems has a clear business impact. First, we can advise aspiring buyers of houses for pay the right price. On the other hand, we can also advise sellers for receive an adequate price that match with their interests.

[NBViewer](https://nbviewer.jupyter.org/github/Dedox-tech/Machine-Learning-Projects/blob/master/Real_estate_2.ipynb) [GitHub](https://github.com/Dedox-tech/Machine-Learning-Projects/blob/master/Real_estate_2.ipynb)

### 2.3 Prediction of the Readmission of U.S Diabetic Patients 

This project aims to predict the readmission of diabetic patients at U.S Hospitals. Given features as a patient information (age, gender, race, weight), medical information (number of medication, number of lab procedures, time in hospital) and other technical features (related with the medical diagnostic), the objective is to predict if the patient will be readmitted or will not in the next 30 days. For the Machine Learning part, we choice a mix of models. First, for the preprocessing phase, we used Principal Components Analysis (PCA) for dimensionality reduction. Next, we tried with two variants of Naïve Bayes classifier (Bernoulli and Gaussian based). After that, we tried traditional models as K-Nearest Neighbors and Logistic Regression. Finally, we applied Artificial Neural Networks (ANN) in this task. Readmission is a measurement that is correlated with quality in hospitals. The more readmission rate, the less score in quality (at least in U.S). Moreover, low quality equals serious penalizations to hospitals. Therefore, if we could identify the patients with high probability of being readmitted, we could create interventions to provide additional assistance in order to avoid future readmission. In this way, we improve quality and save cost for penalties.  

[NBViewer](https://nbviewer.jupyter.org/github/Dedox-tech/Machine-Learning-Projects/blob/master/Healthcare.ipynb) [GitHub](https://github.com/Dedox-tech/Machine-Learning-Projects/blob/master/Healthcare.ipynb)
