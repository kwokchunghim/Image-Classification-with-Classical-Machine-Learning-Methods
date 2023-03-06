# Image-Classification-with-Classical-Machine-Learning-Methods

In this project, we demonstrate solving an image classification task with a subset of the Fashion MNIST dataset with classifical machine learning methods implemented with Scikit-Learn.

Throughout the project, we applied techniques like grid search, cross-validation, hyperparameters tuning, and attempted to use different model structures to optimitize our prediction performance.

Since our binary classification task faces the problem of an imbalanced dataset, average precision instead of accuracy is used as our major metric.

We discovered that both Kernel SVM and K-NN give us satisfactory results (AU-PR = 0.76-0.78), while linear methods such as perceptron and linear SVM underperformed.

Finally, we performed a classification task on train and test data and observed that there is a domain shift in the test data to be addressed.

For more details, please refer to the main.ipynb file for detailed guided explanation.

