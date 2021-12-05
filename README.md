# Data-Analytics-Project
IPL Dataset analysis

## Extracting required features from the dataset.
The dataset does not have the required features directly. Hence, several improtant features have been extracted from different files and compiled into a dataset. This dataset is available as "prediction_df.csv" under the "dataset/ipl" directory. This is the final dataset used for building models.

## To reproduce the results of the DNN Regressor
- Under the file 'deep_neural_network_model.ipynb' navigate to the cell block containing the model build. 
- Set the number of units in each layer to 64, 64 and 32 respectively. 
- Set the activation to be "relu".
- Set the optimizer as adam with a learning rate of 0.001.
- Fit the model to the training data for 200 epochs.