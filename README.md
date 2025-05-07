Classification of FMNIST dataset.
Aside from pipeline for training and evaluating models, three models were implemented:
- A simple CNN without BatchNormalization and Dropout, trained on small amount of epochs to prevent overfitting.
- Same CNN with larger amount of parameters trained, trained for large amount of epochs to show the effect of overfitting
- Second model with BatchNormalization and Dropout layers added, trained on the same amount of epochs to show the effect of BN and Dropout on reducing overfitting
