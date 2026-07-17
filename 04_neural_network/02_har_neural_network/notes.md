so X_train contains 15640 samples (objects -> references) and (40,6) = size of sample
(40,6) => each sample contains 40 timestamps, 6 columns (6 input features = AccX, AccY.....)
data.files => data = np.load("file.name) -> behaves like dictionary and files return keys
tensordataset() used to bundle X and y together so they bhevae like single dataset
dataloader() is used to convert full data to batches




Basic Architecture of Neural Network Implementation
1. Import Dependecies
2. Inspect the data if loading from external file
3. Data Pre Processing -> Converting to float point numbers or encoding the labels
4. If your data is stored as array so convert into Tensors
5. Bind input-output together = TensorDataSet() & divide data into batches using DataLoader()
6. Define the model using class and def forward
7. Create the model
8. Define loss function, optimizer and training loop
9. Evaluate the model (accuracy, confusion matrix etc)
10. Save the model

