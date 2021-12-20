# Final

### First project using python
### About project
First project by using jupyter notebook & python
### Insatllation
It must include sci-kit learn & numpy.
* *need to inastall sci-kit learn package*
  * [install ski-kit learn](https://scikit-learn.org/stable/install.html)
* *need to inastall numpy package*
  * [install numpy](https://numpy.org/install/)
### License
This project is licensed under MIT license.
### Codes explain
Load packages
``` Python
import skleran.~
import numpy.~
```
This statement need time
``` Python
log_reg = sklearn.linear_model.LogisticRegression(solver = 'liblinear',random_state= 0, class_weight = 'balanced', C = 5)
```
**class_weigt = 'balanced'** means uses the values of y to automatically adjust weights

**random_state = 0** means don't shuffle the data

C means Inverse of regularization strength smaller values specify stronger regularization.

``` Python
log_reg.fit(X_train ,y_train)
y_pred = log_reg.predict(X_test)
```
Fit data and predict data
``` Python
print('Accuracy: %.2f' % sklearn.metrics.accuracy_score(y_test, y_pred))
```
Check the accuracy
### How to use
Just run it
