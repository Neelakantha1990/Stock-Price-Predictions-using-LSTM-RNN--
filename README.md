# Stock-Price-Predictions-using-LSTM-RNN--

About the Dataset:-
Train dataset contains  open stock prices of Google from 2012-2016

Test Dataset contains stock prices of Jan 2017 i.e 20 records to predict after training the model with Train set

Steps Followed :-

★Scaled data retrieved from CSV file, created data structures with 60 time steps back & 1 output of open stock prices i.e picked last 3 months price to estimate price of day 1 to day 20 of future dates
★Transformed 2D data structures to 3D using reshape function of numpy library to feed RNN with an ideal input shape
★Designed high dimensionality,stacked LSTM layers to built a robust model with 1.2% data loss, avoided overfitting using drop out regularization on 20% of neurons
★Optimized regressor with powerful Adam's optimizer, fitted RNN to train set with 100 epochs, batch size of 32 to predict continuos output 
★Predicted stock prices were 80% similar to real ones, visualized to see that, curve behavior compared with real price curve
