# Housing Price Prediction using Machine Learning and Neural Networks

I recently completed a data science project where I developed a machine learning and deep learning model to predict housing prices. Here's a brief overview of the project:

**Data Preprocessing:**
- The project started with the exploration of a housing dataset containing information such as location, housing age, room count, population, and more.
- Data preprocessing included handling missing values by replacing them with the median of their respective columns, scaling numeric features to the range [0, 1], and one-hot encoding the categorical feature "ocean_proximity."

**Linear Regression:**
- I implemented a Linear Regression model using both the Least Mean Squares (LMS) method and the Least Squares (LS) method. LMS involved gradient descent with a mean squared error (MSE) cost function. LS used analytical formulas to estimate weights and bias.
- The LMS model achieved an MSE of approximately 4.42 and an MAE of around 1.97, while the LS model achieved an impressive MSE of 0.04 and an MAE of 0.17.

**Neural Network Regression:**
- I also built a neural network model using TensorFlow and Keras for non-linear regression. The model consisted of multiple hidden layers with ReLU activation functions and a linear output layer.
- The neural network model was trained and validated using 10-fold cross-validation.
- The model's performance was evaluated on a test set, achieving an MSE of 185.69 and an MAE of 0.14.

**Data Visualization:**
- I created various data visualizations, including histograms for individual features, overlapping histograms for feature comparisons, and true vs. predicted housing price plots.

This project showcases my skills in data preprocessing, linear and neural network regression, and data visualization. The ability to predict housing prices accurately is valuable in the real estate industry and can be applied to various related fields. If you'd like to learn more about this project or discuss potential collaborations, feel free to connect with me!
