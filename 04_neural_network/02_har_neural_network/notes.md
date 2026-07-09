so X_train contains 15640 samples (objects -> references) and (40,6) = size of sample
(40,6) => each sample contains 40 timestamps, 6 columns (6 input features = AccX, AccY.....)
data.files => data = np.load("file.name) -> behaves like dictionary and files return keys
tensordataset() used to bundle X and y together so they bhevae like single dataset
dataloader() is used to convert full data to batches