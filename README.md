# Forest-Fire-Prediction
## Data Set Information:
The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.

122 instances for each region.

The period from June 2012 to September 2012. The dataset includes 11 attribues and 1 output attribue (class) The 244 instances have been classified into fire(138 classes) and not fire (106 classes) classes.

Attribute Information:

- **Date**: (DD/MM/YYYY) - Day, month (*June to September*), year (2012)
- **Temp**: Temperature at noon (maximum temperature) in Celsius: *22 to 42*
- **RH**: Relative Humidity in %: *21 to 90*
- **Ws**: Wind speed in km/h: *6 to 29*
- **Rain**: Total rainfall in mm per day: *0 to 16.8*



- **Fine Fuel Moisture Code (FFMC)**: *28.6 to 92.5*
- **Duff Moisture Code (DMC)**: *1.1 to 65.9*
- **Drought Code (DC)**: *7 to 220.4*
- **Initial Spread Index (ISI)**: *0 to 18.5*
- **Buildup Index (BUI)**: *1.1 to 68*
- **Fire Weather Index (FWI)**: *0 to 31.1*

### Classes

- **Two classes**: "Fire" and "Not Fire"
## Model Training
- Implemented Linear, Ridge, and Lasso Regression to predict the Fire Weather Index (FWI) using the Algerian Forest Fires dataset.
- Used Grid Search Cross-Validation (Grid Search CV) for hyperparameter tuning the model.
## Result
- Achieved a Mean Squared Error (MSE) of 0.5543 and an R² score of 98.45%.
  
