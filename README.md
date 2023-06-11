# Performance_metrics
Compute Confusion Matrix:

Obtain the predicted labels and the true labels for your classification problem.
Create a 2x2 matrix to represent the confusion matrix.
Count the number of true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN) by comparing the predicted labels with the true labels.
Populate the confusion matrix accordingly.
Compute F1 Score:

Calculate precision and recall using the values from the confusion matrix.
Compute the F1 score using the formula: F1 = 2 * (precision * recall) / (precision + recall).
Compute AUC Score:

Generate different thresholds for classification probabilities or predicted scores.
For each threshold, calculate the true positive rate (TPR) and false positive rate (FPR) using the values from the confusion matrix.
Store the TPR and FPR values in arrays.
Use the numpy.trapz() function to compute the AUC score by integrating the TPR values with respect to the FPR values.
Compute Accuracy Score:

Calculate the accuracy by summing the number of correct predictions (TP + TN) and dividing it by the total number of predictions (TP + TN + FP + FN).
Compute Mean Squared Error (MSE):

Obtain the predicted values and the true values for your regression problem.
Compute the mean squared error by taking the average of the squared differences between the predicted values and the true values.
Compute MAPE (Mean Absolute Percentage Error):

Calculate the absolute percentage error for each prediction by taking the absolute difference between the predicted value and the true value, divided by the true value, and multiplying by 100.
Compute the mean of the absolute percentage errors to obtain the MAPE.
Compute R^2 Error:

Calculate the total sum of squares (TSS) by summing the squared differences between the true values and their mean.
Compute the residual sum of squares (RSS) by summing the squared differences between the predicted values and the true values.
Calculate the R^2 error using the formula: R^2 = 1 - (RSS / TSS).
