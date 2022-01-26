1. Load Data
2. Drop file, start, end columns (unecessary)
3. Apply one-hot encoding to target column (emotion) and get new Dataframe
4. Remove emotion column as output for the dataset
5. Store the emotion column as a target column
6. At this point:
   - X: input dataframe
   - Y: output dataframe (emotions dataframe, one-hot encoded)
7. Split the training and testing dataset: x_train, y_train, x_test and y_test
8. Apply normalization to x_train and x_test
9. No need to apply normalization to y_test and y_train as they are already one-hot encoded.
10. Now apply kNN model to x_train (input) and y_train (output)
11. Check for accuracy etc. with test data
