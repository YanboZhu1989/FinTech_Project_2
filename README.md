# The Coin Whisperer
## USYD FinTech Bootcamp July-2023 Group Project 2
*Group 3: Wasseem, Yanbo, Ferdows, Shayan*

**The code for this project is written in a Jupyter Lab Notebook using a Python Script** 

---
# Project Overview
**Aim: Create the ultimate crypto trading machine**

Considerations:
* Take desired crypto ticker
* Consider available historical data
* Perform machine learning (ML) analysis on the data
  * See next slide for details
* Outputs of ML analysis to be compared and validated
* Add sentiment analysis to the mix and use the combination to:
* Recommend trading strategy (buy/sell and price)
* Output to be displayed and executable on a webpage



# Usage and Installation Guide

# Installs needed for the code
- [yfinance](https://pypi.org/project/yfinance/)
- [arch](https://pypi.org/project/arch/)
- [fear_and_greed](https://pypi.org/project/fear-and-greed/)

Additionally, please ensure the following libraries and dependencies are installed and available for code execution

*For additional context see "Libraries and Dependencies" section of the code:*

### Base Libraries
- pandas, numpy,time, os, Path from pathlib, hvplot.pandas, yfinance, load_dotenv from dotenv  

### Machine Learning
- plt, ticker, mpimg, pyplot, inline from matplotlib, 
- DateOffset from pandas.tseries.offsets  
- svm, StandardScaler, LinearRegression, LogisticRegression, train_test_split, StandardScaler, OneHotEncoder, classification_report, mean_squared_error, r2_score, onfusion_matrix, accuracy_score, and classification_report from [sklearn](https://scikit-learn.org/stable/)
- Prophet from [prophet](https://facebook.github.io/prophet/)  
- Dense and Sequential from [tensorflow](https://www.tensorflow.org)
-  Dense, Activation, Dropout from [keras](https://keras.io)
- arch_model from [arch](https://arch.readthedocs.io/en/latest/)

#### Additional Work
- fear_and_greed
- alpaca_trade_api


# Model Reports and Outputs
1. Logistic Regression
Model output + PNG

        precision    recall  f1-score   support

         0.0       0.00      0.00      0.00       559
         1.0       0.52      1.00      0.68       605

    accuracy                           0.52      1164
   macro avg       0.26      0.50      0.34      1164
weighted avg       0.27      0.52      0.36      1164



       precision    recall  f1-score   support

         0.0       0.00      0.00      0.00       198
         1.0       0.49      1.00      0.66       191

    accuracy                           0.49       389
   macro avg       0.25      0.50      0.33       389
weighted avg       0.24      0.49      0.32       389


  
3. Linear Regression
Model output + PNG

4. GARCH
Model output + PNG

5. SVM
Model output + PNG
      precision    recall  f1-score   support

        -1.0       0.54      0.09      0.16       347
         1.0       0.53      0.93      0.68       385

    accuracy                           0.53       732
   macro avg       0.54      0.51      0.42       732
weighted avg       0.54      0.53      0.43       732



6. Neural Network
Model output + PNG

7. Prophet
Model output + PNG

## Deep Dive: 
Comparison analysis
Model output + PNG



# Links
* [GitHub Repo Link](https://github.com/YanboZhu1989/FinTech_Project_2.git)
* [Project Folder](https://drive.google.com/drive/folders/1nUekI4111UTUd9Az__QJC9vdLuj1YYQK?usp=sharing)
* [Meeting Notes and Project Doc](https://docs.google.com/document/d/1I_i6JGlAO6SgynetaENlZ5KDaHw66uHzHLZBa2tHPOw/edit?usp=sharing)
* [Web Page]()


# Resources and References
- https://edition.cnn.com/markets/fear-and-greed?utm_source=business_ribbon
- https://pypi.org/project/fear-and-greed/
- https://stackoverflow.com/questions/9622163/save-plot-to-image-file-instead-of-displaying-it
- https://arch.readthedocs.io/en/latest/univariate/generated/arch.univariate.GARCH.html#arch.univariate.GARCH
- https://www.investopedia.com/terms/g/garch.asp#:~:text=GARCH%20is%20a%20statistical%20modeling,an%20autoregressive%20moving%20average%20process.
- https://www.capitalone.com/tech/machine-learning/what-is-logistic-regression/
- https://monkeylearn.com/blog/introduction-to-support-vector-machines-svm/
- https://www.investopedia.com/articles/trading/06/neuralnetworks.asp#:~:text=Neural%20networks%20do%20not%20make,using%20traditional%20technical%20analysis%20methods
- https://facebook.github.io/prophet/#:~:text=Prophet%20is%20a%20procedure%20for,several%20seasons%20of%20historical%20data
- Presentation images/artwork  Google Images



