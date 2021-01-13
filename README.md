# CHIL
model file contains structure for the model.
train file runs training and testing of the model.

To run model in training mode -
Set train argument True.
Set discriminator to True to add discriminator network and False to omit discriminator netwrok.

TO run model in test mode -
Set evalPred to True and train to False.
Set predWin to 28 for observation window of 3 years ans prediction window of 7 years
Set predWin to 20 for observation window of 5 years ans prediction window of 5 years
Set predWin to 12 for observation window of 7 years ans prediction window of 3 years
