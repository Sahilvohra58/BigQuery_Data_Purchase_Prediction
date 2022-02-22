# Customer Purchase Prediction

A data of Google analytics for a website is taken and few ML models are made to predict whether the customer will purchase from the site or not.

- `dse_training_data.csv` is the main file that has the training data.
- The data is imported in the `Step_1` file in order to filter it.
- The result of filtering if the `dse_triaining_data_filtered.csv` file.
- Then the filtered data is taken for further consideration to keep only the features that are revelent. The whole process is documented in the `Step_2` file.
- The important features are kept in the `dse_triaining_data_important_features.csv` file.
- Then the file is then taken for making ML models for prediction on the data in the `Step_3` file.
- Due to high imbalance in the dataset labels, upsamplling and downsampling of records is preformed.
- Then data is splited for training and testing purposes.
- Then different models are made to find the best model for the prediction.

