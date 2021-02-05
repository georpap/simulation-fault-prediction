# TEST RIG SIMULATION AND FAULT PREDICTION

**Fault Detection, Isolation and Recovery (FDIR)** 


An IRONHACK/Berlin Machine Learning project by Andres Lucht (github.com/andres2203) and Georgios Papadopoulos (github.com/georpap).



# 1. Background

Data Source: [Condition monitoring of hydraulic systems Data Set ](https://archive.ics.uci.edu/ml/datasets/Condition+monitoring+of+hydraulic+systems)

Examination and evaluation of sensor related data of a hydraulic testing rig. Prediction 4 different target values for stable situation/fault detection.


# 2. Content

data: sensor data
merged_df.pkl: data file



01-load_and_examine_data.ipynb
* Loading, processing and examination of data

02-regression.ipynb
* Regression models to analyze system dependencies 

03-machine-learning.ipynb
* ml part (see applied methods)



# 3. Applied Methods

1. Cross validation on train set
2. Choose best performing algorithm, applied methods
   1. LinearRegression
   2. LogisticRegression
   3. RandomForest
   4. DecisionTree
   5. KNearestNeighbors
3. Feature elimination (RFECV)
4. Evaluation on test set

