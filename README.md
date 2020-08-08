# College Admission Predictor
The dataset for this project is taken from kaggle https://www.kaggle.com/mohansacharya/graduate-admissions.

## Goal
The goal of the project is to predict chance of a student getting admitted into a particular college based on various factors.

### Input Features
* GRE Score
* TOEFL Score
* University Rating
* SOP
* LOR
* CGPA
* Research


## Resources
**Python Version**: 3.7

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn, pickle

## EDA
I looked into various distributions.
Below are some of the highlights

![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%201.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%202.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%203.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%204.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%205.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/eda%206.png)

## Model development
* I used Extra tree Regressor to know the feature importance.

![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/feat.png)

* I used all the regression models to know which model fits best.
* The best model got an accuracy of 82%.

## Results

![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/error.png)
![](https://github.com/yashwanth-gurram/Graduate-Admission/blob/master/Images/accuracy.png)
