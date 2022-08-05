## Simple Vector Regression
In this mini Project, I have used Support Vector regression to predict Salary of an employee with respect to the position and level of the employee.

### Feature Scaling
Here I have scaled all the features to a standard scale of the range -3 to 3, so that features with bigger values does not over power the ones with smaller values
Note: We should always do feature scaling only after splitting of data sets because test set is for testing the model and it should be brand new and untouched, if feature scaling is made befoe the split, then the mean and Standard deviation of the test set are also used in scaling the features, which should not happen, so the dataset should be split followed by feature scaling on training dataset.

### Data Visualization
I have also visualized the output to have a better analysis
Here from the visualization, we can infer that the model has been overfit for the training data, so it might give higher accuracy now, but with different dataset, it will fail to predict an optimal value

