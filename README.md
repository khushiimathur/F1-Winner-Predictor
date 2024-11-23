# F1-Winner-Predictor
This repository contains a machine learning model designed to predict the winner of an F1 race based on several key attributes. The model leverages historical data to make predictions and serves as a helpful tool for enthusiasts and analysts looking to gain insights into race outcomes.
**Features**
The model uses the following attributes to predict the race winner:

1. Lap Times - Historical lap times for each driver during the race.
2. Starting Grid Position - The initial starting position of each driver.
3. Driver Age - The age of each driver at the time of the race.
4. Qualifying Time - The time taken by each driver during qualifying rounds.
5. Weather Conditions - Weather details like temperature, humidity, and precipitation on race day.

**Dataset**
Combined the data collected in [Veronica Nigro's repository](https://github.com/veronicanigro/Formula_1/tree/master/data%20modelling) with average lap times of drivers obtained from [Ergast API](https://ergast.com/mrd/)

**Model Details**
The F1 Winner Predictor uses a Support Vector Machine (SVM) (kernel : polynomial) as the core algorithm to classify the race winner based on the provided attributes.
The model exhibited an accuracy of about 95%.
