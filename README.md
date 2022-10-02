# Road_Section_Time_Series
Road-Section-Time-Series-Prediction
Made by - Daksh Arora


Input File (DATASET.xlsx)
------------------------------------------------------
Original dataset contains 1009 rows and 15 columns.
First column denotes each road section.
Second column denotes the year no. for which parameter values are recorded.
Columns 3 to 15 represents values for parameters 1 to 13.

Task
------------------------------------------------------------------------------------------------------------------------------------------------
We are predicting the parameters Para-9, Para-10, Para-11, Para-12, and Para-13 for year 10 from a 10-year dataset from an IoT sensor on the road.

Model Used
----------------------------------------------------------------------
LightGBM is a gradient boosting framework based on decision trees to increases the efficiency of the model and reduces memory usage. 
We have used Light Gradient Boosting Machine for solving this problem.

Results
-------------------------------------
The RMSE value of the model is 68.76.
