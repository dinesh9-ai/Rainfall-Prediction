# Rainfall-Prediction
## Project mission:
This project is developed to predict the rainfall in millimeters in Ramannapeta of Yadadri-Bhuvanagiri district of Telangana.

### Point to be noted:
This data set is real time dataset and we have done from data pre-processing to metrics evaluation

## Project done by:
Dineshwar Doddapaneni</br>
P.Lakshmi manaswini  (https://github.com/LakshmiManaswini-7)

## Data Source:
Data is collected from open data websites

## Process
Here we used 3 different methods to predict the rainfall,</br>
1)Deep Neural Networks</br>
2)Decision Tree Regressor</br>
3)Random Forest Regressor</br>

### Deep Neural Networks:
Here we have used a deep neural network of 4 hidden layers,</br>
After training the data seeing the MSE we thought this were not the best choice(41 in training)

### Reasons for Deep Neural Networks Failure:
1) We havent managed to get high quantity of data</br>
2) we have trained the machine only with 1000 epochs so due to lack of computational power
3) The architecture was also not sufficent 

### Decision Tree Regressor
Here we  used max depth equal to 5</br>
the R2 score for this model 0.96(train)</br>
the mean absolute error is 0.45(train) 6.9(test)

### Random Forest Regressor
here we used  Random forest Regressor </br>
the R2 score for this model 0.86(train)</br>
the mean absolute error is 1.029(train) 4.8(test)

* out this we felt Decision Tree Regressor algorithm is best 

## Improvements that can be done:
* Here we can collect more data and use neurals networks 
* more computational power could be really usefull for us
