# car_evaluation

This project uses machine learning to predict the condition of a car based on various features.  It employs two classification algorithms: K-Nearest Neighbors (KNN) and Support Vector Machines (SVM).

The project begins by loading car data from a CSV file ('car.data'), then preprocesses the data by converting categorical features (e.g., buying price, maintenance cost, number of doors) into numerical representations using Label Encoding.  The target variable, car condition, is also mapped to numerical values.

The dataset is then split into training and testing sets.  Both KNN and SVM models are trained on the training data.  The trained models then predict the car condition on the test data, and their accuracy is evaluated using the `accuracy_score` metric.  The project outputs the predictions and the accuracy percentages for both models.  This allows for a comparison of the two algorithms' performance on this specific dataset.
