Miguel Candido Aurora Peralta<br>
VIP Project: Transformative AI for Safety<br>
Project Title: Precipitation and Tucson Traffic Accident Frequency

# Stage 2: LSTM Prediction of Accident Hotspots

## Steps for Stage 2
### Data Preprocessing
- Clean dataset
- Encode categorical variables
- Scale numerical features if necessary
- Convert dataset into sequences suitable for LSTM input
### Train/test split
### Model architecture 
- One model includes weather data input, one does not
- Experiment with different configurations of layers, hidden units, dropout regularization, other hyperparameters
- Possibly include additional layers like dense layers for further output processing
- Specify loss function and optimizer
### Train model
- Adjust hyperparameters as needed to prevent overfitting
### Evaluate model
- Evaluate using test set using evaluation methods such as:
    - MSE
    - RMSE
    - MAE
    - MAPE
    - $R^2$
    - prediction accuracy
### Make predictions
### Compare predictions to actual data and assess performance differences between the two models
