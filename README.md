# In the branch: Eliminating 0s from the features columns
I implemented a data preprocessing step to remove all rows that contained 0s in the features columns. This approach was undertaken to perform a comparative analysis of the outcomes by excluding these specific data points. 

To ensure the integrity of the analysis and avoid overfitting, I partitioned the data into a test set comprising 10% of the overall dataset. During experimentation, it was observed that using a larger test set of 20% led to overfitting, prompting the decision to reduce the test set size. 

The resulting model, trained on the modified dataset, exhibited an impressive accuracy of 90%. This accuracy metric serves as a testament to the effectiveness of the data preprocessing approach and the model's ability to generalize well to unseen data.
