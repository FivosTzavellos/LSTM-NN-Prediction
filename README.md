# LSTM-NN-Prediction
Predicting Future Requests in a Data-Buffer using Long Short Term Memory Neural Networks

The problem posed was to predict the next request in a data-buffer i.e. the next number after a sequence of 999 hexadecimals numbers. We solved it by turning hex into int, computing the differences between the previous and the current value and creating a sliding window of 999 numbers, where we predict the 1000th one. We used one-hot encoding to ensure accurate results and an LSTM with 2 hidden layers, 128 neurons on each layer, a dropout of 20% and softmax as the activation function. The hit-rate (count of the times our predicted value matched the real value in the test dataset) was 78%

Co-authored by Efstathia Koutougera

