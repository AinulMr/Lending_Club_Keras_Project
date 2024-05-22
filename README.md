# Personal Project 
____
**Ainul Marzuki Febri**

# Data: Lending Club
Lending Club is a peer-to-peer lending platform founded in San Francisco in 2006 by Renaud Laplanche. The platform connects borrowers seeking personal or business loans with investors looking to invest in those loans. Borrowers apply for loans online, and investors can choose to fund a portion of various loans to spread the risk. Lending Club enables easier access to credit for borrowers and attractive investment opportunities for investors.

# Our Goal
With historical data on loans and information on whether a borrower defaulted (charge-off) or not, can we build a model that can predict whether a borrower will repay their loan? Thus, in the future when a new prospective customer comes along, we can assess whether they are likely to repay their loan.

# Conclusion
This project successfully built a binary classification model to predict whether loans in Lending Club will be fully paid (class 1) or charged off (class 0) with 89% accuracy. Through the stages of data exploration, preprocessing (addressing missing data and handling categorical variables), and overfitting using techniques such as dropout and early stopping, the model showed excellent performance in detecting fully paid loans (class 1) with perfect recall (1.00) and high precision (0.88). However, the model had difficulty in detecting charged off loans (class 0) with a low recall (0.44), despite a very high precision (0.99). This suggests that while the model is effective in predicting fully paid loans, further improvements are needed to enhance the detection of charged off loans.

Recommendations for further improvement include:
- Balancing the dataset if there is an imbalance between classes.
- Exploration of additional features that can help detect class 0 better.
- Using oversampling or undersampling techniques to overcome class imbalance.
