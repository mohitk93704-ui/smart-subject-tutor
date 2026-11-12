Subject: Machine Learning (B.Tech CSE Core)
Topic 1: Supervised vs Unsupervised Learning
Supervised Learning is a type of Machine Learning in which a model is trained using labelled datasets, where both input data and their correct output labels are provided. The model learns the relationship between inputs and outputs to predict results for unseen data. It is mainly divided into two categories: Classification (predicting discrete categories) and Regression (predicting continuous numerical values).

Unsupervised Learning is a type of Machine Learning in which a model is trained using unlabelled datasets, where only input data is provided without predefined output labels. The algorithm identifies hidden patterns, structures, and relationships within the data. Common techniques include Clustering and Association Rule Learning.

Topic 2: Classification vs Regression
Classification is a supervised learning technique used to predict discrete categories or class labels. It determines which group an input belongs to based on patterns learned from training data. For example, classifying an email as Spam or Not Spam. Common algorithms include Logistic Regression, Decision Trees, Naive Bayes, and Support Vector Machines (SVM).

Regression is a supervised learning technique used to predict continuous numerical values based on input features. It establishes a mathematical relationship between independent variables and a dependent variable. For example, predicting house prices based on area, location, and number of rooms. Common algorithms include Linear Regression, Polynomial Regression, and Decision Tree Regression.

Topic 3: Linear Regression and Logistic Regression
Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values by establishing a linear relationship between independent variables (features) and a dependent variable (output). It finds the best-fit line by minimizing the sum of squared differences between actual and predicted values using the Least Squares Method.

The mathematical equation is:

Y
=
m
X
+
C
Y=mX+C
Where:

Y = Predicted output

X = Input feature

m = Slope or coefficient

C = Intercept

Logistic Regression is a supervised classification algorithm used to predict the probability of an input belonging to a particular class. Unlike Linear Regression, it uses the Sigmoid Function to convert the output into a probability between 0 and 1. A threshold, typically 0.5, is used to assign the final class label.

The Sigmoid Function is:

σ
(
z
)
=
1
1
+
e
−
z
σ(z)= 
1+e 
−z
 
1
​
 
Topic 4: Decision Tree and Random Forest
Decision Tree is a supervised Machine Learning algorithm used for both classification and regression tasks. It works like a flowchart in which internal nodes represent feature-based decisions, branches represent possible outcomes, and leaf nodes represent final predictions. It selects the best feature for splitting data using measures such as Information Gain, Entropy, or Gini Index.

Random Forest is an ensemble learning algorithm that combines multiple Decision Trees to improve prediction accuracy and reduce overfitting. It uses Bootstrap Aggregation (Bagging), where different trees are trained on randomly selected subsets of training data and features. For classification, the final prediction is based on majority voting, whereas regression uses the average of predictions.

Topic 5: Overfitting vs Underfitting
Overfitting occurs when a Machine Learning model learns the training data too closely, including noise and unnecessary details. As a result, it achieves very high accuracy on training data but performs poorly on unseen testing data. It is commonly controlled using Regularization, Cross-Validation, Pruning, and increasing training data.

Underfitting occurs when a Machine Learning model is too simple to capture the underlying patterns and relationships in the training dataset. Consequently, it performs poorly on both training and testing data. It can be reduced by using a more complex model, adding relevant features, and reducing excessive regularization.

Topic 6: K-Nearest Neighbors (KNN) and Support Vector Machine (SVM)
K-Nearest Neighbors (KNN) is a supervised Machine Learning algorithm used for classification and regression. It predicts the output of a new data point by identifying its K closest data points in the training dataset using distance metrics such as Euclidean Distance. In classification, the majority class among the K nearest neighbors determines the prediction. KNN is called a lazy learning algorithm because it does not build an explicit training model.

Support Vector Machine (SVM) is a supervised Machine Learning algorithm primarily used for classification. It identifies an optimal decision boundary called a Hyperplane that separates different classes with the maximum possible margin. The closest data points to the hyperplane are called Support Vectors. SVM can also handle non-linear data using the Kernel Trick.

Topic 7: Clustering and K-Means Algorithm
Clustering is an unsupervised Machine Learning technique used to group similar data points into clusters based on their features and characteristics. Data points within the same cluster have high similarity, while points belonging to different clusters have low similarity. It is commonly used in customer segmentation, image segmentation, and pattern recognition.

K-Means Clustering is an unsupervised learning algorithm that divides a dataset into K predefined clusters. It initially selects K centroids and assigns each data point to its nearest centroid using distance calculations. The centroids are repeatedly recalculated until the cluster assignments become stable or a stopping condition is reached. K-Means aims to minimize the Within-Cluster Sum of Squares (WCSS).

Topic 8: Artificial Neural Networks (ANN)
Artificial Neural Network (ANN) is a computational model inspired by the structure and functioning of the human brain. It consists of interconnected processing units called Neurons, arranged into three main layers: Input Layer, Hidden Layer, and Output Layer. Each connection has an associated weight, and neurons use activation functions to introduce non-linearity. ANN learns patterns from training data by adjusting weights and biases using Backpropagation and Gradient Descent.

Topic 9: Gradient Descent and Backpropagation
Gradient Descent is an optimization algorithm used to minimize the loss or error function of a Machine Learning model. It works by repeatedly updating model parameters in the opposite direction of the gradient of the loss function. The learning rate controls the size of each parameter update. Common variants include Batch Gradient Descent, Stochastic Gradient Descent (SGD), and Mini-Batch Gradient Descent.

The update rule is:

θ
=
θ
−
α
∇
J
(
θ
)
θ=θ−α∇J(θ)
Where:

θ
θ = Model parameters

α
α = Learning rate

J
(
θ
)
J(θ) = Cost function

Backpropagation is a learning algorithm used in Artificial Neural Networks to calculate the gradients of the loss function with respect to network weights. It propagates the error backward from the output layer to the hidden layers using the Chain Rule of Calculus. These gradients are then used by Gradient Descent to update weights and minimize prediction errors.

Topic 10: Model Evaluation Metrics
Model Evaluation Metrics are statistical measures used to determine how accurately a Machine Learning model performs on unseen data. Different metrics are used depending on whether the task is classification or regression.

Accuracy: Measures the proportion of correctly predicted observations out of total observations.

Precision: Measures how many predicted positive cases are actually positive.

Recall: Measures how many actual positive cases are correctly identified.

F1-Score: Represents the harmonic mean of Precision and Recall.

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

Root Mean Squared Error (RMSE): Represents the square root of MSE and measures prediction error in the original unit.

Topic 11: Bias-Variance Tradeoff
Bias is the error introduced when a Machine Learning model makes overly simplistic assumptions about the underlying data. High bias causes Underfitting because the model cannot capture complex patterns.

Variance refers to the model's sensitivity to small changes in training data. High variance causes Overfitting because the model learns specific details and noise from the training dataset.

Bias-Variance Tradeoff is the concept of balancing bias and variance to achieve good generalization performance. A suitable model should maintain an appropriate level of complexity to minimize total prediction error on unseen data.