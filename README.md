# Fetal Health Prediction

## Summary
The objective of
this project is predicting fetal health accurately based on
various features and classify it from the range of 1 to 3
(“Normal”, “Suspect” and “Pathological”). We used cardiotocography data set with 2126 fetal cardiotocograms
(CTGs) and 23 features. We applied kNN, Decision Tree,
Random Forest, and various ensemble methods and observed their performance (test accuracy). In addition, impurity based feature importance analyzed with Random Forest and boosting
algorithms to figure out the most important feature in the
process of prediction. As a result of the project, we found
that boosting methods (XGBoost and Histogram Gradient
Boosting) are the models that have the best performance
and MSTV (mean value of short term variability) is the most
important feature in the prediction based on XGBoost and
ASTV (percentage of time with abnormal short term variability) is the most important feature in the prediction based on Random Forest.

### Test Accuracy

<img width="439" alt="Screen Shot 2022-06-19 at 6 47 30 AM" src="https://user-images.githubusercontent.com/69660509/174479666-e1f4af78-7e46-40e2-8cfe-31eb6621dfac.png">

- The F1-score combines the precision and recall of a classifier into a single metric by taking their mean.

### Feature Importance

<p float="left">
  <img width="290" height="290" alt="Screen Shot 2022-06-19 at 6 48 53 AM" src="https://user-images.githubusercontent.com/69660509/174479715-2f9cec81-9985-428a-a899-ff58098c3303.png">
  <img width="290" height="290" alt="Screen Shot 2022-06-19 at 7 00 07 AM" src="https://user-images.githubusercontent.com/69660509/174479818-074cc87f-7c56-4010-b7cc-3d9d26bca2c2.png">
</p>

## Dataset

- The dataset for this project are “Cardiotocography Dataset” provided by [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). Cardiotocography dataset contain 2126 fetal cardiotocograms(CTGs) with 23 features. The CTGs were classified by three expert obstetricians and a consensus classification label assigned to each of them. The 23 features consist of the following data fields.
<img width="463" height="563" alt="Screen Shot 2022-06-20 at 10 20 48 PM" src="https://user-images.githubusercontent.com/69660509/174709517-2aa42e92-9f1b-41d7-b771-b7f85a888801.png">



## Downside & Future Direction

- Future direction on this study could be done in the way of more bountiful observations coupled with outside of cardiotcography data such as more related information of a mother and genetic information. Plus, various multicolinearity troubleshooting methods among histogram columns will also be a great idea. Lastly, beyond just figuring out mere importance of features, applying various feature extraction techniques to explain feature health would be ideal.

## Reference

[1] Causes of infant mortality:infant mortality. Centers for Disease Control and Prevention, 2021.<br/>
[2] Cardiotocography. Cardiotocography — Wikipedia, the free
encyclopedia, 2021. [Online; accessed 05-December-2021].<br/>
[3] Centers for Disease Control and Prevention. Fetal deaths, 2020.<br/>
[4] D. Dua and C. Graff. UCI machine learning repository, 2017.<br/>
[5] S. Ghosh, M. Raghunath, and J. K. Sinha. Encyclopedia of
animal cognition and behavior, 2017.<br/>
[6] R. K. Jones and E. Witwer. Induced abortion in the united
states, May 2020.<br/>
[7] Minnesota Center for Health Statistics. Infant and fetal mortality, 2021.<br/>
[8] Reuter. Startup gets fda clearance for device that can monitor
baby’s heart rate, Mar 2020.<br/>
[9] H. Sahin and A. Subasi. Classification of the cardiotocogram
data for anticipation of fetal risks using machine learning
techniques, 2015.<br/>
[10] A. Subasi, B. Kadasa, and E. Kremic. Classification of
the cardiotocogram data for anticipation of fetal risks using
bagging ensemble classifier. Procedia Computer Science,
168:34–39, 2020. “Complex Adaptive Systems”Malvern,
PennsylvaniaNovember 13-15, 2019.