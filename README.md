# Machine-Learning
Build Machine Learning models in python (or R) and some notes about machine learning algorithms

### the scope of algorithms
* Logistic Regression (l1, l2, elastic net regularization)
* Support Vector Machine
* Decision Trees
* Ensemble learning (voting classifier, bagging, boosting, stacking)
* Dimensionality Reduction
* linear regression (in R)

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
