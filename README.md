# Machine-Learning
This repository is dedicated to exploring the exciting domain of Machine Learning, acquiring an understanding of the various machine learning concepts and algorithms, and gaining practical experience.

# Files
* [California Housing Price Prediction.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/California%20Housing%20Price%20Prediction.ipynb) - This Jupyter notebook explore the use of various ML algorithms to develop models to predict housing prices in the state of California. The models covered in this notebook are `Linear Regression`, `Decision Trees`, `Random Forest`, and `Support Vector Regression` (SVR). Model otimization techniques utilized to find the best combination of hyperparameters are `Grid Search` and `Random Search`

* [Titanic.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/Titanic.ipynb) - Exploring various ML classifiers—`Random Forest`, `Stochastic Gradient Descent`**(SGD)**, `Support Vector Classifier`**(SVC)**, and `K-Nearest Neighbors`**(KNN)**—to develop models that predict which passengers survived the Titanic shipwreck.

* [MNIST Classifier.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/MNIST%20Classifier.ipynb) - The task is to build a machine learning model that accurately classifies the handwritten digits contained in the `MNIST dataset` into their respective categories `(0 through 9)` based on the pixel values of the images. The MNIST dataset is a popular benchmark dataset in the field of machine learning and computer vision. It consists of a large collection of `28x28` pixel `grayscale images` of handwritten digits (0-9).

* [Linear Models.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/Linear%20Models.ipynb) - This notebook explores training of the `linear regression` model using two different ways:
  * Using a `“closed-form” equation` that directly computes the model parameters that best fit the model to the training set (i.e., the model parameters that minimize the cost function over the training set).
  * Using an iterative optimization approach called `gradient descent (GD)` that gradually tweaks the model parameters to minimize the cost function over the training set. Also covers the following variants of **GD**: `batch GD`, `mini-batch GD`, and `stochastic GD`.

* [Polynomial Regression.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/Polynomial%20Regression.ipynb) - Deals with `polynomial regression`, a more complex model that can fit `nonlinear datasets`. Polynomial regression has more parameters than linear regression and is therefore more prone to overfitting the training data. Thus, this notebook also explores how to detect whether or not the model is `overfitting` the training data, by making use of `learning curves`.

* [Regularized Linear Models.ipynb](https://github.com/KelvinMumo/Machine-Learning/blob/main/Regularized%20Linear%20Models.ipynb) - Regularization reduces the chances of overfitting the training set. For a linear model, regularization is typically achieved by constraining the weights of the model. The regularized linear models studied include:
  * `Ridge regression`
  * `Lasso regression` and
  * `Elastic net`
 
  These models implement three different ways to constrain the weights. This notebook also covers the concept of `early stopping` which is a very different way to regularize `iterative learning` algorithms such as `gradient descent` by stopping training as soon as the validation error reaches a minimum. 
