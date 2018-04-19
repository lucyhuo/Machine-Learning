# Machine-Learning
Build Machine Learning models in python (or R) and some notes about machine learning algorithms

### the scope of algorithms
* Logistic Regression (Regularized Logistic Regression. Use different metrics to evaluate models, such as precision, recall, f1 score, ROC and AUC to evaluate model performance. Implemented Softmax Regression with Gradient Descent.)
* Support Vector Machine (SVM classifier and SVM regressor. Use linear kernel and Gaussian RBF kernel.)
* Decision Trees
* Ensemble learning (voting classifier, bagging, boosting, stacking)
* Dimensionality Reduction (PCA, LDA, tSNE and other popular dimensionality reduction methods. Visualizations of reduction result.)
* linear regression (in R. EDA, Residual analysis, model validation, error diagnosis and remediation)

### Prerequisites
make sure you have python3 installed on your machine.
install pip3 for installing python module
run this pip command to install all the required modules
```
pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
```

Also, make sure you have R kernel available to Jupyter notebook

In R console, run
```
install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))
devtools::install_github('IRkernel/IRkernel')
IRkernel::installspec()
```
