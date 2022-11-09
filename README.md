# Neural_Network_Charity_Analysis

## Overview of the Analysis
The project analysis was conducted through Machine Learning and Neural Networks. Through creating a binary classification that will be used to predict if applicatns who were funded by Alphabet Soup will be successful.
The steps that were taken are:
- Preprocessing data
- Compile, Train, Evaluation of the model
- Model optimization

## Results
### Preprocessing
Target in model: IS_SUCCESSFUL Column
Features in mode: All columns except IS_SUCCESSFUL
Neither Targets or Features: Dropped columns were EIN, NAME, due to them not having impact on outcome.

### Compile, Train, and Evaluate
4 Hidden layers:
- 1st hidden layer= 110 RELU
- 2nd hidden layer= 80 RELU
- 3rd hidden layer= 40 SIGMOID
- 4th hidden layer= 20 SIGMOID

<img width="733" alt="Screenshot 2022-11-09 104710" src="https://user-images.githubusercontent.com/108282027/200875998-eb5a37c9-91c0-4735-9bb4-f527ff3dfba5.png">

The model didn't reach the target of 75%, with the overall accuracy for the model being 72.5%.

<img width="746" alt="Screenshot 2022-11-09 104814" src="https://user-images.githubusercontent.com/108282027/200876211-5a3402e0-98b2-4b39-8bf6-d3f4f780c30d.png">

I tried to change the first layer to sigmoid from relu, however the accuracy has dropped by .3% to 72.2%.

<img width="737" alt="Screenshot 2022-11-09 105029" src="https://user-images.githubusercontent.com/108282027/200876741-ce156a5f-d057-4082-ab8e-53b9108aa65a.png">

## Summary
After optimization the model accuracy had the highest score of 72.5%. The loss/gain of the accuracy might have been caused by the model being overfitted. The model can be optimized further by cleaning or removing neural networks, increasing data points, and removing features. 
