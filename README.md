# ICDM
Preprocessing: These steps have to be taken for both male and female cohorts.
1. extraction - shoes how data is extracted from All of Us database and preprocessed. 
2. flatten - creates one hot encodeing data
3. padding2 - creates 3-month disjoint time periods for time-series.

model file contains structure for the model.
train file runs training and testing of the model.
For running train file for male or female, set male or female argument to true, respectively.

To run model in training mode -

Set train argument True.

Set discriminator to True to add discriminator network and False to omit discriminator netwrok.


To run model in test mode -

Set evalPred to True and train to False.

Set predWin to 28 for observation window of 3 years ans prediction window of 7 years

Set predWin to 20 for observation window of 5 years ans prediction window of 5 years

Set predWin to 12 for observation window of 7 years ans prediction window of 3 years

