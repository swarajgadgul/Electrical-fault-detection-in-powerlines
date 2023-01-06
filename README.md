# Electrical fault detection in transmission lines
<center> <img src="https://lge-ku.com/sites/default/files/2021-03/Transmission_Falling_Tree_033021a.gif" width="1000" height="400"> </center>

## Problem Statement:
<p>

The transmission line is the most crucial part of the power system. The requirement of power and its allegiance has grown up exponentially over the modern era, and the prominent role of a transmission line is to transmit electric power from the source area to the distribution network. The electrical power system consists of so many complex dynamic and interacting elements that are always prone to disturbance or an electrical fault.
    </p>
<p>

** What are Electrical Faults? **

Normally, a power system operates under balanced conditions. When the system becomes unbalanced due to the failures of insulation at any point or due to the contact of live wires, a short–circuit or fault, is said to occur in the line. Faults may occur in the power system due to the number of reasons like natural disturbances (lightning, high-speed winds, earthquakes), insulation breakdown, falling of a tree, bird shorting, etc.</p>

## Model results:
| **Model**               | **Training Accuracy** | **Model Accuracy Score** | **F1 score** | **Precison score** | **Recall score** | **Roc Auc Score** | 
|-------------------------|-----------------------|--------------------------|--------------|--------------------|------------------|--------------------|
| Decision Tree           | 99.96                 | 100.00                   | 0.995065     | 0.994619           | 0.995512         | 0.995425           |
| XGBClassifier           | 100.00                | 99.75                    | 0.997312     | 0.995528           | 0.999102         | 0.997609           |
| Random Forest           | 99.96                 | 99.71                    | 0.996865     | 0.994638           | 0.999102         | 0.997220           |
| Support Vector Machines | 98.33                 | 97.50                    | 0.972401     | 0.997170           | 0.948833         | 0.973251           |
| Logistic Regression     | 71.22                 | 71.14                    | 0.549122     | 0.997636           | 0.378815         | 0.689019           |          |   

## Conclusion
We have performed EDA, preprocessing, build different models,

Decision Tree is giving the best Result with 100 percent accuracy,with other metrics and is doing a great job till now in Fault Detection followed by Random Forest, Classifier,XGB Classifier, than the rest of the models because it's able to predict all the signals in most efficient manner while in other models there are cases where there is actually fault but the model is not able to identify it.Logistic Regression is giving the worst accuracy
