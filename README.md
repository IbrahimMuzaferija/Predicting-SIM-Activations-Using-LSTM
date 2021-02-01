# Predicting SIM activations using Long Short-Term Memory (LSTM) Recurrent Neural Networks

## Introduction

This project implements LSTM RNN for continious value prediction. 

First, data is selected, then cleaned and analyzed. The image below represents the raw data histogram.

<p align="center"><img src="https://raw.githubusercontent.com/IbrahimMuzaferija/Predicting_SIM_Activations_Using_LSTM/master/raw-dataset-histogram.png"></p>


In Data Analysis phase, SIM activations are resampled - the frequency with best stationarity is choosen for model creation.

<p align="center"><img src="https://raw.githubusercontent.com/IbrahimMuzaferija/Predicting_SIM_Activations_Using_LSTM/master/resampling-activation-frequency.png"></p>


The image below shows the model prediction results across the time.

<p align="center"><img src="https://raw.githubusercontent.com/IbrahimMuzaferija/Predicting_SIM_Activations_Using_LSTM/master/subscriber-activations-model-result-graph.png"></p>


In the image below, model predictions across one working week are shown. It's valuable to point out that the model generalizes well and handles random fluctuations.

<p align="center"><img src="https://raw.githubusercontent.com/IbrahimMuzaferija/Predicting_SIM_Activations_Using_LSTM/master/model-prediction-accuracy-graph.png"></p>

While this model is constructed to forecast only one time-step, it's possible to reconstruct it to predict a series of time-steps.
