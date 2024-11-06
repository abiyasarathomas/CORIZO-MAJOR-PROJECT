**WINE QUALITY ANALYSIS - MACHINE LEARNING AND DATA SCIENCE**
Here we will predict the quality of wine on the basis of given features. We use the wine quality dataset available on Internet for free. This dataset has the fundamental features which are responsible for affecting the quality of the wine. By the use of several Machine learning models, we will predict the quality of the wine

**ABSTRACT**
Wine quality certification is crucial for the wine industry, as it directly influences consumer trust and market value. The objective of this project is to develop a machine learning model to predict wine quality using a dataset of red wine samples (RWD) with eleven distinct physiochemical attributes. Five machine learning (ML) models were initially trained and tested on the RWD, with Random Forest (RF) and Extreme Gradient Boosting (XGBoost) emerging as the top-performing algorithms.

For enhanced performance, we applied feature selection using the RF and XGBoost models to identify the top three most influential features from the original eleven. We then conducted further ML analysis on the reduced feature set. Various visualizations highlight feature importance based on both XGBoost and RF models. Predictions of wine quality were made using these critical features, which were identified as fundamental through the feature selection process.

The XGBoost classifier achieved 100% accuracy when trained and tested across three configurations: without feature selection, with RF-based feature selection, and with only key attributes. In scenarios with essential features, RF also demonstrated improved performance. To fine-tune model accuracy, the RF classifier underwent hyperparameter optimization and validation.

Additionally, cluster analysis was employed to address potential collinearity among features, reducing the number of predictors without compromising model performance. This approach helped streamline the model and enhance the accuracy of wine quality predictions.

**Importing libraries and Dataset:**
**Pandas** is a useful library in data handling.
**Numpy** library used for working with arrays.
**Seaborn/Matplotlib**are used for data visualisation purpose.
**Sklearn** – This module contains multiple libraries having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.
**XGBoost** – This contains the eXtreme Gradient Boosting machine learning algorithm which is one of the algorithms which helps us to achieve high accuracy on predictions.

**STEPS INCLUDED**
1) LOAD THE DATASET AND NECESSARY LIBRARIES(I've used kaggle to perform the tasks)
2) PERFORM BASIC OPERATION TO DISPLAY FEW ROWS, SORT AND REMOVE COLUMNS.
3) EDA(Exploratory Data Analysis) METHODS ARE USED FURTHER ON THE DATASET
4) FINALLY, MACHINE LEARNING TECHNIQUES SUCH AS LINEAR REGRESSION AND CLASSIFICATION MODELS ARE CREATED

**CONCLUSION**
Interest in the wine industry has grown recently, which begs for industrial expansion. To increase wine production and sales, corporations are investing in cutting-edge technologies. For each of these procedures, wine quality certification is essential and necessitates expert human wine testing. We utilised samples from the red wine dataset (RWD) with eleven distinct physiochemical properties. With the initial sample of RWD, five ML models were trained and evaluated. We evaluated the effectiveness of the RF and XGBoost classifiers based on accuracy, recall, F1 scores, and support before introducing them as ML models to predict wine quality. Using these two ML methodologies, the top three features are chosen from a total of eleven features, and ML analysis is performed on the other features. Various plots are used to represent the feature importance based on the XGBoost model and RF. Wine quality was predicted using significant characteristics (also known as essential factors) that were demonstrated to be meaningful in at least three feature selection approaches. When trained and evaluated without feature selection, with feature selection (RF), and with key variables, the XGBoost classifier displayed 100% accuracy (features found important in feature selection). The performance of the RF classifier was improved in the presence of necessary variables. Finally, we have trained an RF classifier, calibrated it, and adjusted its hyperparameters to evaluate the accuracy of its predictions. We also carried out cluster analysis to manage collinearity and limit the number of predictors without compromising model accuracy. Overall, all classifiers performed better when trained and evaluated utilizing key factors. The main aspect of this study is the value of data production techniques and the significance of feature selection. In the future, large datasets can be used for studies, and additional ML and deep learning methods could be investigated for predicting wine quality.


THE FILE IN WHICH I'VE DONE THE ANALYSIS IS ATTACHED IN THIS REPOSITORY
