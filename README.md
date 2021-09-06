# Module_14_Challenge

This Jupyter Notebook provides an analysis on an algorithmic trading system using two different machine learning algorithms and a comparison as to which performs better.


---

## Baseline trading algorithm results

Looking at the classification report of the graphic below, this model has a 61% accuracy and the only downside would be there recall percentage of 31 in predicting -1.0. 

![Baseline Trading Results]
(Starter_Code/svm_model.PNG)

---

## Tuned trading algorithm results

Looking at the classification report for the tuned algorithm, it has a 56% accuracy for a window size of 8 months. As I increased the window, the overall accuracy fell along with the precision and recall predicting -1.0.


---

## Backtested new model

This model has a 57% percent accuracy, but fails to predict for -1.0 under precision and recall. This model performed worse than the baseline model and the tuned model. 

![Tuned Trading Results]
(Starter_Code/logistic_model.PNG)

---

## Contributors

* Allen Wong