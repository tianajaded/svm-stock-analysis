# svm-stock-analysis

The goal of the SVM analysis was to build a classification model that predicts the movement of stock prices (either 'up' or 'down') based on historical data. We selected relevant features, including open, close, high, low, adjusted close, volume, dividend amount, and split coefficient, to train the SVM model. The ROC and AUC were used to evaluate the model's performance. The ROC curve graphically represents the trade-off between true positive rate (sensitivity) and false positive rate (1-specificity). An AUC value close to 0.50 suggests that the model's predictive ability is no better than random chance.Our analysis revealed an AUC in the range of 0.50 to 0.55, indicating that the SVM model struggled to discriminate between 'up' and 'down' movements in stock prices. Essentially, it means that the svm model is no better at predicting price movement than random chance.

Notes and results are recorded in the Notebook. 
